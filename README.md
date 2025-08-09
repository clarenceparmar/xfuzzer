# XFuzzer

**XFuzzer** is a powerful, cross-platform fuzzing tool designed for penetration testers and security researchers.  
It supports fuzzing HTTP requests with custom wordlists, headers, cookies, and advanced options to help discover vulnerabilities in web applications.

---

## Features

- Cross-platform: Works on Windows, Linux, and macOS  
- Supports GET, POST, and other HTTP methods  
- Customizable wordlists for fuzzing parameters (FUZZ keyword)  
- Add custom headers and cookies  
- Control concurrency with threads and rate limiting  
- Follow redirects optionally  
- Real-time progress with detailed status  
- Easy-to-use GUI built with JavaFX  

---

## Screenshots

![Main Fuzzing Form](docs/screenshots/fuzzform.png)  
![Process List](docs/screenshots/processlist.png)

---

## Installation

1. Download the latest release from the [Releases](https://github.com/yourusername/xfuzzer/releases) page  
2. Extract the archive  
3. Run the executable:

```bash
# On Windows
xfuzzer.exe

# On Linux/macOS
./xfuzzer
