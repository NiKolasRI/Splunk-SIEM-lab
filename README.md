🛡️ Splunk-SIEM-lab
Hands-on Splunk SIEM lab covering installation, configuration, log analysis, SPL queries, threat detection, and security investigations.
## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Project Objectives](#2-project-objectives)
- [3. Tools and Technologies](#3-tools-and-technologies)
- [4. Installation](#4-installation)
  - [4.1 Splunk Enterprise Installation](#41-splunk-enterprise-installation)
- [5. Initial Configuration](#5-initial-configuration)
  
# 1. Introduction
# 🛡️ Splunk SIEM Lab – SOC Analyst Portfolio

![Splunk](https://img.shields.io/badge/SIEM-Splunk-000000?logo=splunk)



This project documents my practical experience with Splunk Enterprise, a Security Information and Event Management (SIEM) platform widely used in Security Operations Centers (SOC).

The main objective is to develop practical cybersecurity skills through log analysis, security monitoring, threat detection, and incident investigation.

This lab simulates real-world SOC Analyst tasks and demonstrates how SIEM technology can help identify and investigate suspicious activities.

# 2. Project Objectives

The main objectives of this project are:

- Install and configure Splunk Enterprise.
- Understand SIEM architecture and functionality.
- Collect and ingest security logs.
- Analyze Windows and Linux events.
- Learn Search Processing Language (SPL).
- Identify suspicious activities and security threats.
- Detect brute-force login attempts.
- Investigate potential security incidents.
- Build dashboards for security monitoring.
- Develop practical SOC Analyst skills.

# 3. Tools and Technologies

| Tool                 |             Purpose             |

| Splunk Enterprise    |  SIEM and log analysis          |

| Windows 11           |  Main operating system          |

| Linux / Ubuntu       |  Linux log analysis             |

| SPL                  |  Search and analysis language   |

| VMware               |  Virtualization environment     |

| Windows Event Logs   |  Security event monitoring      |

# 4. Installation

## 4.1 Splunk Enterprise Installation

The first step is installing Splunk Enterprise.

Installation process:

1. Download Splunk Enterprise from the official website.

    You can download it from the Official website:   https://www.splunk.com/en_us/download/splunk-enterprise.html
<img width="2463" height="1292" alt="image" src="https://github.com/user-attachments/assets/43450dac-89d7-4400-bcac-14abc275c4bb" />


To download Splunk, first create an account. Keep in mind that Splunk Enterprise offers a free trial. After the trial period, a paid license may be required depending on the intended use and licensing option.  click the **"Free Trial and Downloads"** button in the top-right corner of the website. Then, select the version that is compatible with your operating system and download Splunk Enterprise. 

<img width="1236" height="1191" alt="image" src="https://github.com/user-attachments/assets/b514b69c-a095-4a53-becb-77aa8b4de0f4" />

2. Run the Installer

Once the download is complete, open the downloaded file to start the installation process.


3. Accept the license agreement.

   Accept the license aggrement to proceed to the next step of the installation.
  
4. Create an administrator account.
  To use Splunk you need to create an administrator account to access and  manage the platform  .
<img width="483" height="375" alt="image" src="https://github.com/user-attachments/assets/b40fa902-8033-40f5-9d15-406cfde3bb46" />

5. Complete the installation.
  The final step is to finish the installation process. Once completed, Splunk will be installed on your system and ready to use.

<img width="484" height="370" alt="image" src="https://github.com/user-attachments/assets/84a49b2d-2cb9-4a5e-b208-568245b24c96" />


6. Start Splunk Enterprise.

# 5. Initial Configuration

After completing the installation and logging in, the Splunk Enterprise interface should look like this:

<img width="2497" height="1297" alt="image" src="https://github.com/user-attachments/assets/e9063c9b-7ade-4c65-96ee-9bf88a9c5b7e" />

If we want to monitor our local system using Splunk, we don't necessarily need to install additional applications.

However, if we want to analyze logs from other systems, simulate security threats, and perform more advanced security investigations, we can set up a virtual machine to create a controlled lab environment.

If you're interested in setting up a virtual machine, you can check out my guide here: [Virtual Machine Setup]().




<img width="289" height="436" alt="image" src="https://github.com/user-attachments/assets/d0ed9f0a-2cdb-4842-a44f-0fc1c884b776" />

The left sidebar provides access to the main sections of Splunk Enterprise, allowing users to navigate between different tools and functionalities.

In this section, we will focus only on the most important and commonly used features of Splunk Enterprise for SOC Analysts.

The first section displayed after logging into the platform is where most activities takes place. All logs and security monitoring appear in this section.

# 6. Exploring our first logs.

Our computers perform numerous activities, generating a large number of logs. As SOC Analysts, our job is to collect and analyze these logs to identify relevant security information and detect potential threats.


Lets start by exploring  our computer´s logs using Splunk.

First, on the Splunk Enterprise home page, locate the "Add Data" option. This feature allows users to configure data sources and collect logs from their computers for further analysis.

<img width="1680" height="937" alt="image" src="https://github.com/user-attachments/assets/9f17e10a-04d8-4816-ad80-05fb6cac9831" />


After clicking the "Add Data" option, users will be redirected to the following page:

<img width="1207" height="972" alt="image" src="https://github.com/user-attachments/assets/0bd0c789-ee69-4cfd-b395-05fe99e62f35" />

On this page, users can choose the data ingestion method that best suits their needs. Splunk Enterprise allows users to upload log files manually or configure automatic log collection from supported data sources.

The final step is to select the logs we want to collect from our system. Users can choose from a wide range of available log sources depending on their needs. Each user can monitor and analyze logs generated by their own computer.

<img width="1125" height="1384" alt="image" src="https://github.com/user-attachments/assets/29429a38-0c56-4b3f-855d-a1b1ed45d19f" />

Once all these steps have been completed, the collected logs can be viewed and analyzed in the **Search & Reporting** section of Splunk Enterprise.

<img width="1479" height="1149" alt="image" src="https://github.com/user-attachments/assets/80fb4a88-7748-47b1-a53f-2f3dd1a0fcc9" />


# 7. Practical SOC Investigations

This section contains hands-on security investigations performed using Splunk Enterprise. Each investigation includes SPL queries, log analysis, screenshots, findings, and conclusions.

### Investigations
  
1. [Windows Log Analysis](SOC-Investigations/01-Windows-Log-Analysis.md)
2. [Failed Login Detection](SOC-Investigations/02-Failed-Login-Detection.md)
3. [Security Event Analysis](SOC-Investigations/03-Security-Event-Analysis.md)




## 12. Key Learning Outcomes

Through this portfolio, I aim to develop practical experience in:

- SIEM administration and configuration.
- Security log analysis.
- SPL query development.
- Authentication monitoring.
- Threat detection.
- Incident investigation.
- Security monitoring and reporting.

## 13. Conclusion

This project provides a practical introduction to SIEM operations and security monitoring using Splunk Enterprise.

It is part of my continuous learning journey in cybersecurity, with a particular focus on Blue Team operations and SOC Analyst responsibilities.

More investigations and practical exercises will be added as the lab develops.

---

**Author:** NiKolasRI  
**Focus:** Cybersecurity | Blue Team | SOC Analyst
