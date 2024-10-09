# HIPAA Compliance Checklist for Technological Systems

## Plan of Action
Take each high-level category in the Systems of Focus section below and create an approach to address each key area. Determine reasoning behind each approach and provide details or examples with the primary subareas. Compile documented researched data into a checklist format and elaborate on each in the form of a research paper to describe details of the key areas.

## Systems of Focus

- #### Executive Summary

- #### Introduction

- #### Objectives

- #### HIPAA Overview

- #### Technological Implications with HIPAA

- #### Scope of Systems Covered (Table of Contents)

- #### Hardware
    - Laptop/Desktop Computers
    - Mobile Devices (phones, tablets)
    - External Storage Devices (USB storage drive, external hard drive, etc.)
    - Printers/Copiers
    - Medical Devices (e.g., Heart monitors, insulin pumps)
    - Wearable Health Devices (e.g., Smart watch with medical tracking applications, etc.)
    - Diagnostic Equipment (e.g., MRI, X-Ray, Ultrasound, CT or PET Scanners, etc.)
    - Remote Patient Monitoring Devices (e.g., Continuous glucose monitors, sleep, etc.)

- #### Communication Tools
    - Email
      - Email Standard Usage
      - Email Archival
    - Fax
      - Analog Fax (traditional)
      - Internet Faxing
      - FoIP
      - Email to Fax
      - Cloud Faxing
      - Fax Modem (computer as a fax machine)
    - Analog phone line
    - IP phone line
    - Video Conference Systems (Teams, Zoom, etc.)
    - Nurse Call Systems
      - Old-fashioned pager-styled
      - Others…?
    - Phone systems
      - VoIP
      - Others...?
    - Collaboration & Individual Messaging Systems & Software (SMS, WhatsApp, Slack, Teams, etc.)

- #### Software Applications and Data Management Systems
    - Mobile Device Management (MDM) and Active Directory (AD) Systems
    - Remote Desktop Connectivity
    - Antivirus-related Software
    - Email Encryption Service
    - Password Management Systems
    - Data Encryption and Transmission Tools
    - Digital Forms
      - PDFs
      - Form software (e.g., Google Forms, Jotform)
    - File Backup Systems
      - Local File Storage Systems (File archival, image storage, etc.)
      - Cloud Storage Systems (Dropbox, Google Drive, etc.)
    - Databases
      - EHR Systems
      - eMAR Systems
      - Billing Software
      - Appointment Scheduling Software
      - Patient Portals
      - Clinical Decision Support Systems
      - Laboratory Information Systems
      - Prescription Management Software
      - Patient Relationship Management Tools
      - Health and Wellness Applications

- #### Networking Technologies
    - Firewall (SonicWall, pfSense, OPNsense)
    - Switch Equipment
    - Virtual Local Area Network (VLAN)
    - Virtual Private Network (VPN)
      - Incoming
      - Outgoing
    - Utilized Servers
      - Internal VPN Server
      - Application Server
      - Email Server
      - Print Server
      - Database Server
      - File Server
      - Web Server (typically intranets)
      - Proxy Server
      - DNS Server (doesn’t store PHI but can be fatal if compromised)
    - FTP/SFTP Connections
    - SSL vs TLS Protocols (standards to be in place)
    - Wireless Network Management System (Meraki dashboard, Ubiquiti dashboard)

- #### Network Monitoring Tools
    - Considerations
      - Who can access the tool
      - Where data from the tool is stored
    - Tools
      - Intrusion Detection and Prevention Systems (IDPS)
      - Network Performance Monitoring Systems (NPMS)
      - Security Information and Event Management (SIEM)
      - Application Performance Monitoring (APM – for critical systems)
      - Network Traffic Analysis (e.g., Wireshark)
      - Network Detection and Response Systems (NDR)
        - May be coupled with Endpoint Detection and Response (EDR)
          - e.g., Microsoft Defender for Endpoint coupled with Microsoft Defender for Identity, Cisco Secure Endpoint coupled with Cisco Secure Network Analytics
        - May be done by only using IDPS in some cases

- #### Authentication Devices & Methods
    - Password/PIN
    - RFID (Badge scanners, keycards, proximity cards, etc.)
    - NFC (Mobile devices, NFC cards, NFC badges, etc.)
    - Bluetooth
    - Motion Detection Sensors (coupled with RFID/NFC/Bluetooth)
    - Biometric (Fingerprint, iris, voice recognition, etc.)
    - Smart Cards
    - OTP Tokens
      - Hardware OTP Tokens (RSA SecureID, YubiKey)
      - Authentication App OTP Tokens (Microsoft Authenticator, Duo)
      - SMS OTP Tokens
      - Email OTP Tokens
    - USB and Miscellaneous Hardware Security Keys
      - U2F
      - FIDO2
    - Public/Private Keys
    - QR/Bar Code (Scanning each time rather than registration for future OTPs)
    - Magnetic Stripe Cards
    - Geolocation (coupled with another or multiple methods)
    - Multimodal Authentication

- #### Authentication methods can be broken down into five categories:
    - Something you know (e.g., Password)
    - Something you have (e.g., RSA SecureID)
    - Something you are (e.g., Iris scanner)
    - Where you are
    - When you are

- #### Appendix
    - Checklist
    - Technical Specifications (details about encryption standards and other misc. info)
    - Detailed Risk Matrix
    - Additional Resources (Links to things such as NIST Guidelines, HIPAA Security Rule, HHS.gov, etc.)
    - Glossary
    - Legal Disclaimer
    - References
