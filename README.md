# Forensica---Web-Log-Analyzer
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/) [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/blob/main/CONTRIBUTING.md)  

# Overview
**Forensica Web Log Analyzer** is a powerful forensic tool by **SecureBlueAcademy** designed to analyze web server logs (IIS, Nginx, Apache) and detect various web attacks. The tool provides comprehensive analysis capabilities with output options in both CSV and HTML formats for easy reporting and further investigation.

# Features
- Supports IIS, Nginx, and Apache web server logs
- Detects multiple types of web attacks including:
  - SQL Injection attempts
  - Cross-Site Scripting (XSS) attacks
  - Directory Traversal attempts
  - Remote File Inclusion (RFI) attacks
  - Brute Force attacks and other suspicious activities
- Generates detailed reports in CSV or HTML format
- Lightweight and fast processing
- Command-line interface for easy automation

# Usage
Basic Command

**Forensica Web Log Analyzer.exe -t LOG_TYPE -i INPUT_PATH -o OUTPUT_FILE_NAME --csv/--html**

Parameters Required:
  - -t, --type	Log type (iis, nginx, apache)
  - -i, --input	Path to input log file or directory
  - -o, --output	Output file name (without extension)
  - --csv	Output in CSV format
  - --html	Output in HTML format
  - -v, --verbose	Show verbose output
  - -h, --help	Show help message	

# Examples
Analyze IIS logs and generate HTML report:
  - **Forensica Web Log Analyzer.exe -t iis -i C:\logs\iis\ -o report --html**

Analyze Apache logs and generate CSV report:
  - **Forensica Web Log Analyzer.exe -t apache -i /var/log/apache2/access.log -o apache_report --csv**

Analyze Nginx logs with verbose output:
  - **Forensica Web Log Analyzer.exe -t nginx -i nginx_access.log -o nginx_results --html -v**

# Tool's Output
For parsing and analyzing the web logs, use a cmd or powershell with valid commands.
![image](https://github.com/user-attachments/assets/82f89882-76b9-447d-986a-5ab14335541b)

CSV Output look like this giving information about the logs and attacks detected.
![image](https://github.com/user-attachments/assets/e08c171c-3874-49cd-b0f5-6416ae43f3b6)

HTML output provide a chart with attack distribution.
![image](https://github.com/user-attachments/assets/6c9d3e59-cc2a-40a7-a2dd-8d4dfa03b4b5)

HTML output also provide filtering option for more detailed investigations.
![image](https://github.com/user-attachments/assets/f44b911e-5eae-4105-8e47-1b5ca8456ce9)

# Feedback & Contributions  

We welcome your feedback and contributions to help improve Forensica - Web Log Analyzer! Please feel free to submit bug reports, feature requests, and pull requests.  

Wanted to Connect: Here is our LinkedIn Profile: https://www.linkedin.com/company/secureblue-academy

## License  

Forensica-Web Log Analyzer is an open-source, free to use for anyone.

Happy Forensics!


