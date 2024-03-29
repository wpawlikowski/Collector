# Collector
Phishing simulations and pentests with awesome Blazor app 🛡️ 🧪 

// by [ethical.blue](https://ethical.blue/)

![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/live.png)

![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/blazor.png)

# Demo account
Attached database file has some sample data. Login credentials are login: `demo` and password: `demo`.

# Deploying Collector application to web server

Tutorial here: [https://ethical.blue/textz/n/5](https://ethical.blue/textz/n/5)

## Sample application scenario

Overview of example phishing simulation (pentest) using Collector application.

0x01. Complete documents with company or people which will be pentested. Act legally.

0x02. Prepare e-mail addresses (you can buy domains), message templates and program or script to send e-mails. You can also send e-mails manually.

Here comes Collector application. 🙂

0x03. Create campaigns and links in Collector app web panel.

0x04. Embed links in messages and send prepared e-mails to targets.

0x05. Monitor which links have been clicked. There are also IP addresses and timestamps collected.

0x06. Print elegant reports for your boss/customer.

0x07. Educate employees and retest on a regular basis.

# Version history
v1.0 — Initial release

# Features
+ Mobile friendly web control panel protected with password
+ Incorrect panel login detection to prevent hacking
+ Create links and organize them into campaigns
+ Monitor link activity during a pentest
+ Monitor executed files with file campaigns
+ Show to your boss/customer elegant reports
+ Move completed campaigns to archive
+ No expensive MS SQL database needed (app uses file)

# Hosting requirements
Collector is ASP.NET Core Blazor Server application for .NET 6.0

# Web interface
Enjoy mobile friendly Collector interface.

## Mobile friendly
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/mobilefriendly1.png)

## Login form
Web control panel is password protected.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector1.png)

## Incorrect login detection
Monitor attacks on login panel with incorrect login detection.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector2.png)

## Links organized into campaigns
Organize your links into campaigns for clarity and easy management.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector3.png)

## Link details
There are a lot of link details including IP addresses and timestamp.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector4.png)

## File campaigns
File campaigns allow you to monitor executed (harmless) payloads on tested machines.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector5.png)

## View data collected during file campaigns
Executable used in file campaigns collects username, machinename and BIOS serial number.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector6.png)

## Create elegant reports
Probably every boss and customer likes to have it all served on a plate.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector7.png)

## Sample link campaign report
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector8.png)

## Sample file campaign report
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector9.png)

## Move old campaigns to archive
Completed campaigns can be moved to archive for clarity.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector10.png)

## Harmless executable for file campaigns
Payload provided for file campaigns is NOT malware.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector11.png)

## Printing reports
Print pentest reports if you need paper version of documents.
![image](https://github.com/ethicalblue/CollectorApp/blob/main/images/collector12.png)
