# Scripts for automating processes in the OS.

## AddRouteToKi.ps1
When a vpn client connects, the use of the default vpn gateway is disabled and a static route to the network behind vpn is added.

## auditUser.ps1
User activity audit script. Tracks the inclusion, shutdown of the OS, login and logout of users in the OS.

## ShutdownByTimer.bat
Turning off the computer on a timer. Time is indicated in hours.

## VeeamBackup.ps1
Script to backup virtual machines using vim. The script automates the creation of backups in Veeam Community Edition 9.0 and later.

## BackupDatabases1C.bat
Backup file databases 1C.

## Email_Good_m.ps1 and Email_bad_d.ps1
Sending an email with a script.

## Disable_activesync_and_outlook_web_app.ps1
Here is a PowerShell script that remotely disables ActiveSync and Outlook Web App services for a user in an enterprise domain network, using Kerberos authentication.
You can save this script as Disable_activesync_and_outlook_web_app.ps1 and run it with the specified email address as an argument, like this: 

.\Disable_activesync_and_outlook_web_app.ps1 "username@example.com"

