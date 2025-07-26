# 🔍 Keylogger Detection Tool

A comprehensive Python-based security tool designed to detect potential keyloggers and malicious processes on Windows systems. This tool provides real-time scanning capabilities with an intuitive interface for cybersecurity professionals and system administrators.

## ✨ Features

- **Process Analysis**: Scans running processes for suspicious behavior patterns
- **File System Monitoring**: Detects suspicious files in common malware locations
- **Real-time Progress**: Visual progress bars and status updates
- **Comprehensive Reporting**: Generates detailed JSON reports for further analysis
- **Lightweight Design**: Minimal resource usage with maximum detection capability
- **Portable Executable**: Can be compiled to a standalone .exe file

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- Windows OS
- Administrator privileges (recommended)

### Installation
```bash
git clone https://github.com/SkaiWkr/Scanner
cd Scanner
```

### Usage
```bash
python scanner.py
```

### Executable
```bash
*#Just download the latest Release and run it as admin#*
```

## 📊 Detection Methods

The tool employs multiple detection techniques:

- **Keyword Analysis**: Searches for suspicious terms in process names and command lines
- **Path Analysis**: Identifies processes running from unusual locations
- **File Pattern Matching**: Detects suspicious file creation patterns
- **Behavioral Analysis**: Monitors for keylogger-like behaviors

## 🛡️ Security Features

- **Whitelist Protection**: Excludes legitimate system processes
- **False Positive Reduction**: Smart filtering to minimize incorrect detections
- **Detailed Reporting**: Provides context for each detected threat
- **Safe Operation**: Read-only scanning with no system modifications

## 📈 Sample Output

```
═════════════════════════════════════════════════════════════
🔍 KEYLOGGER DETECTION TOOL
═════════════════════════════════════════════════════════════
🔎 Scanning running processes...
[████████████████████] 100%
🔎 Checking suspicious files...

📊 SCAN RESULTS
═════════════════════════════════════════════════════════════
✅ No suspicious processes detected
✅ No suspicious files detected
💾 Full report saved: keylogger_report_20250726_143052.json
```

## 🔧 Technical Details

**Built with:**
- Python 3.x
- psutil library for process monitoring
- Native Windows APIs for system integration

**Detection Accuracy:**
- Low false positive rate through intelligent filtering
- Comprehensive coverage of common keylogger techniques
- Regular updates to detection patterns

## 📝 Requirements

```txt
psutil>=5.8.0
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is designed for legitimate security purposes only. Users are responsible for ensuring compliance with applicable laws and regulations. The tool should only be used on systems you own or have explicit permission to test.

## 👨‍💻 Author

**Siddhant Mandal**  
Computer Science & Cybersecurity Student  
*Building tools to make digital environments safer*

## 🔗 Connect

- LinkedIn: [linkedin.com/in/sigmandal]
- GitHub: [@SkaiWkr]

---

*⭐ If this tool helped you secure your system, please consider giving it a star!*

---
