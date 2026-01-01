# Powershell_scripts

This repository contains a collection of PowerShell (and some Batch-assisted) scripts designed to assist IT administrators, system engineers, and network administrators with daily operational tasks.

The scripts focus on monitoring, diagnostics, automation, and reporting, with an emphasis on clarity, safety, and real-world usability.

# 🚀 This project also represents my first hands-on experience with PowerShell, built while learning and applying best practices.

# 🎯 Purpose of This Repository

Provide practical PowerShell tools for daily IT operations

Automate common administrative checks

Offer clear, well-documented scripts suitable for learning and real use

Serve as a growing personal IT toolkit

All scripts are written to be easy to understand, modify, and extend.

# 📂 Script Categories
# 🧑‍💼 Active Directory

Scripts related to user and directory management, such as:

User creation wizards

Account checks

Reporting and validation

# 🌐 Networking & DNS

Scripts for network diagnostics and name resolution, such as:

DNS Health Checks

Connectivity tests

Resolution validation for critical servers

# 💻 System & Server Monitoring

Scripts for inspecting system health and status, including:

Disk space checks

System information reports

Uptime and basic diagnostics

# 📊 IT Toolkits

Menu-driven scripts that combine multiple tools into a single interface, for example:

PowerShell IT Toolkit

Daily operational checks

Read-only diagnostic utilities

# 🛠 Supported Systems

The scripts in this repository are intended for and tested on:

Windows Server

2012 R2

2016

2019

2022

Windows Client

Windows 10

Windows 11

Supported Roles

Domain Controllers

DNS Servers

File Servers

Application Servers

IT / Admin Workstations

# ⚙️ Requirements

PowerShell 5.0 or higher

Network connectivity (for network-related scripts)

Appropriate permissions depending on the script

# 📌 Most scripts do not require Domain Admin privileges unless explicitly stated.

# 🔐 Safety & Best Practices

Scripts are designed to be read-only by default

No configuration changes are performed unless clearly documented

Uses Microsoft-supported and non-deprecated cmdlets

No external modules required (unless explicitly mentioned)

Safe to run in production environments when used as intended.

# 🚀 How to Use

Clone the repository:

git clone https://github.com/yonathan-toledano/Powershell_scripts.git


Open PowerShell as Administrator

(Optional) Allow script execution for the current session:

Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass


Navigate to the script folder and run the desired script:

.\ScriptName.ps1


# 📄 Each script includes detailed comments explaining:

What the script does

What each section is responsible for

How and when it should be executed

# 📌 Project Philosophy

Clear comments over clever code

Safety before automation

Practical tools over theoretical examples

Continuous improvement and learning

# 📈 Future Plans

Expand the IT Toolkit with additional modules

Add security and audit-focused scripts

Improve reporting and automation features

Refactor selected scripts into reusable modules

# 👤 Author

Yonathan Toledano
GitHub: https://github.com/yonathan-toledano
This repository is actively evolving as part of my learning journey in PowerShell and IT automation.
Feedback, suggestions, and improvements are always welcome.
