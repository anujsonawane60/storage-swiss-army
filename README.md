# 🛠️   storage-swiss-army
 

A comprehensive collection of Python scripts for file system analysis, organization, and management. Perfect for system administrators, developers, and anyone who needs to manage large amounts of data efficiently.

## 📋 Features

### 🔍 Drive Scanner (`drive_scanner.py`)
- **Large File Detection**: Find files exceeding customizable size thresholds (default: 10MB)
- **Heavy Folder Analysis**: Identify directories consuming the most disk space
- **Complete System Scan**: Handles hidden files and system directories
- **Real-time Progress**: Live progress indicator with scan statistics
- **Cross-platform**: Works on Windows (C:\), Linux, and macOS
- **Export Results**: Save detailed reports to timestamped files

### 📁 File Extension Sorter (`file_sorter.py`)
- **Smart Organization**: Automatically sort files by extension into organized folders
- **Batch Processing**: Handle thousands of files efficiently
- **Customizable Rules**: Define your own sorting categories and patterns
- **Safe Operations**: Backup and rollback functionality
- **Duplicate Handling**: Smart conflict resolution for existing files

## 🚀 Quick Start

### Prerequisites
- Python 3.6 or higher
- No external dependencies required (uses only standard library)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/file-toolkit.git
cd file-toolkit
```

2. Make scripts executable (Linux/macOS):
```bash
chmod +x *.py
```

### Usage Examples

**Scan your entire C: drive for large files:**
```bash
python drive_scanner.py
# Enter: C:\
# Enter: 50  (for files >50MB)
```

**Sort messy download folder:**
```bash
python file_sorter.py
# Enter: /path/to/downloads
# Choose sorting strategy
```

## 📊 Sample Output

```
🔍 DRIVE SCANNER - Large Files & Heavy Folders Finder
================================================================
📁 Enter directory path to scan: C:\
📏 Enter size threshold in MB: 10

🔍 Starting scan of: C:\
📏 Looking for files larger than: 10.00 MB
| Scanning... Files: 125,847 | Total Size: 485.23 GB | Large Files Found: 23

📊 SCAN RESULTS
================================================================
⏱️  Scan completed in: 127.45 seconds
📁 Files scanned: 125,847
💾 Total size scanned: 485.23 GB
🔍 Large files found: 23

🗂️  LARGE FILES (>10.00 MB):
----------------------------------------------------------------------
 1.    2.84 GB | C:\Users\John\Videos\vacation_2024.mp4
 2.  856.73 MB | C:\Program Files\Game\textures.pak
 3.  234.56 MB | C:\Windows\System32\drivers\storage.sys
```

## 🔮 Planned Features

- **Duplicate File Finder**: Identify and manage duplicate files across drives
- **Disk Usage Visualizer**: Generate charts and graphs of storage usage
- **File Age Analyzer**: Find old files that haven't been accessed recently
- **Smart Backup Tools**: Intelligent backup suggestions based on file importance
- **Network Drive Scanner**: Extend scanning capabilities to network locations
- **File Compression Analyzer**: Identify files that would benefit from compression

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

### Contribution Guidelines
- Follow PEP 8 style guidelines
- Add docstrings to all functions
- Include error handling for file operations
- Test on multiple operating systems when possible
- Update README.md if adding new features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports & Feature Requests

Found a bug or have a great idea? Please open an issue on GitHub:
- **Bug Reports**: Include your OS, Python version, and steps to reproduce
- **Feature Requests**: Describe the use case and expected behavior

## 📚 Documentation

For detailed documentation and advanced usage examples, visit our [Wiki](../../wiki).

## ⭐ Show Your Support

If this toolkit helped you organize your files, please give it a star ⭐ on GitHub!

---

**Made with ❤️ by developers, for developers who value organized file systems.**
