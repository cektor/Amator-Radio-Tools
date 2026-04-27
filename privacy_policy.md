# Privacy Policy for Amateur Radio Tools Pro

**Effective Date:** April 27, 2026  
**Last Updated:** April 27, 2026

## Introduction

This Privacy Policy describes how Amateur Radio Tools Pro ("we," "our," or "us") collects, uses, and protects your information when you use our mobile application (the "App"). We are committed to protecting your privacy and ensuring transparency about our data practices.

Amateur Radio Tools Pro is designed specifically for amateur radio operators and provides various tools including DMR/NXDN ID lookup, APRS tracking, propagation forecasting, antenna calculations, digital logbook, morse code tools, band plans, QTH locator conversion, VSWR calculations, DX cluster monitoring, and beacon tracking.

## Information We Collect

### 1. Personal Information
We do **NOT** collect any personally identifiable information (PII) such as:
- Names
- Email addresses
- Phone numbers
- Physical addresses
- Payment information
- User accounts or profiles

### 2. Location Information
**When and Why We Access Location:**
- **QTH Locator Tool:** We request location access only when you explicitly use the "Current Location" feature in the QTH Locator calculator
- **Purpose:** To automatically calculate your QTH locator grid square based on your current coordinates
- **User Control:** Location access is entirely optional and only activated when you tap the "Current Location" button
- **Data Handling:** Location coordinates are processed locally on your device and are not stored or transmitted to external servers

### 3. Network Access
**Internet Connection Usage:**
- **RADIS Tool:** Queries DMR/NXDN ID databases via RADIOID.net API
- **APRS Tracking:** Retrieves APRS data from APRS.FI API
- **Propagation Forecast:** Fetches real-time solar data from HamQSL.com/N0NBH
- **DX Cluster:** Accesses DX spots from DX Summit (dxsummit.fi)
- **Purpose:** All network requests are made to provide real-time amateur radio data and services
- **Data Transmission:** Only necessary query parameters (callsigns, IDs) are sent to respective APIs

### 4. Device Storage
**Local Data Storage:**
- **Digital Logbook:** QSO records are stored locally on your device using Android's Room database
- **User Preferences:** App settings and preferences are stored locally
- **Cache Data:** Temporary API responses may be cached locally to improve performance
- **No Cloud Sync:** All data remains on your device and is not synchronized to cloud services

## Permissions Explained

### Required Permissions

#### 1. INTERNET Permission
- **Purpose:** Essential for accessing amateur radio databases and real-time data
- **Usage:** 
  - DMR/NXDN ID lookups via RADIOID.net
  - APRS data retrieval from APRS.FI
  - Solar propagation data from HamQSL.com
  - DX cluster spots from DX Summit
- **Data Sent:** Only necessary query parameters (callsigns, radio IDs)
- **No Personal Data:** We never send personal information through internet requests

#### 2. ACCESS_NETWORK_STATE Permission
- **Purpose:** To check network connectivity before making API requests
- **Usage:** Prevents app crashes and provides better user experience by detecting offline status
- **Benefit:** Allows the app to show appropriate messages when internet is unavailable

### Optional Permissions

#### 3. ACCESS_FINE_LOCATION Permission
- **Purpose:** Exclusively for the QTH Locator tool's "Current Location" feature
- **When Requested:** Only when you tap "Current Location" button in QTH Locator
- **Usage:** Calculates your Maidenhead grid square (QTH locator) from GPS coordinates
- **User Control:** Completely optional - you can use all other app features without granting this permission
- **Data Handling:** Location is processed locally and never transmitted or stored

#### 4. READ_EXTERNAL_STORAGE Permission (Android 12 and below)
- **Purpose:** For importing ADIF/CSV logbook files
- **Usage:** Allows you to import existing QSO logs from external files
- **User Control:** Only activated when you choose to import logbook data
- **Scope:** Limited to files you explicitly select

#### 5. WRITE_EXTERNAL_STORAGE Permission (Android 10 and below)
- **Purpose:** For exporting logbook data to ADIF/CSV files
- **Usage:** Saves your QSO logs to external storage for backup or sharing
- **User Control:** Only used when you choose to export your logbook
- **Modern Alternative:** On newer Android versions, we use scoped storage for better security

## Data Usage and Sharing

### What We Do NOT Do
- **No Data Collection:** We do not collect, store, or analyze user behavior data
- **No Analytics:** We do not use analytics services or tracking tools
- **No Advertising:** We do not display ads or use advertising networks
- **No Third-Party Sharing:** We do not share any user data with third parties
- **No User Profiles:** We do not create user accounts or profiles
- **No Cloud Storage:** We do not store any user data on remote servers

### Third-Party Services
We interact with the following external APIs solely to provide amateur radio services:

#### RADIOID.net
- **Purpose:** DMR/NXDN ID database lookups
- **Data Sent:** Radio IDs and callsigns for lookup purposes
- **Privacy Policy:** https://radioid.net/privacy

#### APRS.FI
- **Purpose:** APRS station tracking and information
- **Data Sent:** APRS callsigns for station lookup
- **Privacy Policy:** https://aprs.fi/privacy

#### HamQSL.com (N0NBH)
- **Purpose:** Solar propagation data and band conditions
- **Data Sent:** No personal data, only requests for current solar indices
- **Service:** Public amateur radio propagation service

#### DX Summit (dxsummit.fi)
- **Purpose:** Real-time DX cluster spots
- **Data Sent:** No personal data, only requests for current DX spots
- **Service:** Public DX spotting network

## Data Security

### Local Data Protection
- **Encryption:** All local data is protected by Android's built-in security features
- **Access Control:** Only our app can access its stored data
- **No Backup to Cloud:** App data is not included in automatic cloud backups

### Network Security
- **HTTPS:** All API communications use secure HTTPS connections
- **Minimal Data:** We only send the minimum necessary data for each request
- **No Sensitive Data:** We never transmit sensitive personal information

## Data Retention

### Local Storage
- **Logbook Data:** Stored locally until you delete entries or uninstall the app
- **Settings:** Retained until app is uninstalled
- **Cache:** Automatically cleared based on Android system policies

### No Remote Storage
- We do not store any user data on remote servers
- All data remains on your device under your control

## Children's Privacy

Amateur Radio Tools Pro is designed for amateur radio operators who typically hold valid radio licenses. The app does not knowingly collect information from children under 13. If you believe a child has provided information to us, please contact us immediately.

## Your Rights and Choices

### Data Control
- **Location Access:** You can revoke location permission at any time through Android settings
- **Data Deletion:** Uninstalling the app removes all locally stored data
- **Network Access:** You can disable internet access for the app, though this will limit functionality

### App Permissions Management
You can manage all app permissions through:
1. Android Settings → Apps → Amateur Radio Tools Pro → Permissions
2. Grant or revoke permissions as needed
3. The app will function with limited features if permissions are denied

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do:
- We will update the "Last Updated" date at the top of this policy
- Significant changes will be communicated through app updates
- Continued use of the app after changes constitutes acceptance of the new policy

## Contact Information

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**Developer:** ALG Yazılım  
**Email:** [Contact information to be added]  
**App Version:** 1.0.0  
**Platform:** Android

## Compliance

This Privacy Policy complies with:
- Google Play Developer Policy
- Android App Privacy Requirements
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) guidelines

## Amateur Radio Community

As fellow amateur radio operators, we understand the importance of privacy and data security in our community. This app is built by hams, for hams, with respect for our shared values of technical excellence and ethical operation.

## Technical Implementation

### Open Source Components
This app uses various open source libraries and components. None of these components collect personal data or transmit information without your explicit consent.

### API Rate Limiting
We implement responsible API usage to respect the resources of third-party services and ensure continued availability for all amateur radio operators.

### Offline Functionality
Many app features work offline, including:
- Antenna calculations
- Morse code tools
- Band plan reference
- VSWR calculations
- QTH locator conversion (without GPS)
- Logbook viewing (locally stored data)

---

**73 de Amateur Radio Tools Pro Development Team**

*This Privacy Policy is effective as of April 27, 2026, and applies to all users of Amateur Radio Tools Pro.*