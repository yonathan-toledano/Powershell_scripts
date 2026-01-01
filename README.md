##Powershell_scripts##

This repository contains basic PowerShell and Batch scripts that provide useful network and system administration tools.
The purpose of this repository is to offer simple tools for daily IT and sysadmin use.

🚀 This project also represents my first hands-on experience with PowerShell.

Active Directory User Creation Wizard

An interactive Batch + PowerShell wizard for creating new users in Active Directory via the command line.

The script prompts the administrator for user details and automatically creates the user in a predefined Organizational Unit (OU).

✨ Features

Interactive user creation wizard

Collects user information:

First Name

Last Name

Username

Password

Phone Number

Automatically sets:

sAMAccountName

UserPrincipalName

Display Name

Telephone number

Description

Enables the user account (userAccountControl = 512)

Error handling and success messages

📋 Requirements

Windows environment with:

Active Directory Domain Services

Permissions to create users in the target OU

PowerShell installed

Run as Administrator (recommended)

🚀 Usage

Clone the repository:

git clone https://github.com/yonathan-toledano/Powershell_scripts.git


Run the script:

ActiveDirectoryUserWizard.bat


Enter the requested information:

First name

Last name

Username

Password

Phone number

The script will create the user and display a success or error message.

🧩 Configuration

Before using the script, update the following values to match your environment:

$ouDN = 'OU=OU name* Users,DC=domain,DC=on'
$userPrincipalName = $user + '@domain.on'


🔧 Replace:

OU name* Users with your actual OU name

domain.on with your real domain

⚠️ Security Notes

Passwords are entered and processed in plain text

Not recommended for production environments without improvements

Suggested enhancements:

Use Read-Host -AsSecureString

Convert to a full PowerShell script

Add password policies and validation

📌 Future Improvements

 Check if user already exists

 OU selection menu

 Group assignment

 Force password change at first logon

 Logging to file

 Secure password handling

👤 Author

Yonathan Toledano
GitHub: https://github.com/yonathan-toledano
