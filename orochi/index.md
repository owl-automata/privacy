# Privacy Policy for Orochi  
**OWL Automata**  
**Last updated:** 2025-12-03

---

## 1. Introduction

Orochi is a desktop application developed by **OWL Automata** (founded in 2023).  
The application integrates with **Google Calendar**, **Microsoft Outlook / Office 365 Calendar**, and authentication services to trigger **Building Management System (BMS)** automation events.  

Orochi does **not** use calendar data for any other purpose and does **not** store, sell, or share personal data.

---

## 2. Desktop Application Notice (Tauri)

Orochi is a **desktop application built with Tauri**.  
User authentication with Google and Microsoft occurs through secure OAuth2 flows using the system browser.

The application **does not operate a remote backend server** that stores user information.  
All user data accessed by the app is processed **locally on the user's device**, unless explicitly required for automated BMS functionality.

---

## 3. Data We Access

Orochi may request access to the following information:

### Google APIs
- Google Calendar event metadata (title, start time, end time)
- Calendar identifiers
- Availability (busy/free)
- Basic Google profile information required for login (email address)

### Microsoft Graph APIs
- Outlook Calendar event metadata
- Calendar identifiers
- Calendar availability

---

## 4. How We Use the Data

Orochi uses calendar information **only for:**
- Detecting scheduled events  
- Sending BMS automation commands (e.g., HVAC, room control, lighting triggers)

Orochi **does not**:
- Use data for marketing  
- Use data for analytics  
- Sell or share user data  
- Use data for profiling  
- Store calendar content externally  

All processing happens **locally** on the user's device.

---

## 5. Data Storage

Orochi does **not store** any personal data on external servers.

The app may temporarily store:
- OAuth session information (in memory only)
- OS-protected authentication tokens (local secure storage)

No calendar data is saved permanently.

---

## 6. Authentication Tokens

### Google
Google OAuth tokens are handled using secure system browser flows and are not transmitted to external servers.

### Microsoft
Microsoft account tokens are stored **only on the user’s device** using the **operating system’s secure credential storage**.  
No authentication tokens are uploaded to any server owned by OWL Automata.

---

## 7. Google API Services – Limited Use Compliance

Orochi complies with the **Google API Services User Data Policy**, including the **Limited Use** requirements.

Specifically:
- Google user data is **not transferred** to external servers  
- Google user data is **not stored** permanently  
- Google user data is **not used** for advertising, profiling, or analytics  
- Google user data is used **only** for calendar-based automation events  

---

## 8. Microsoft Graph API Compliance

Orochi uses Microsoft Graph Calendar scopes strictly for:  
- Reading calendar events  
- Triggering on-device BMS automation  

The app does **not** store or share Microsoft user data.

---

## 9. Data Sharing

Orochi does **not share** any personal data with:
- Third parties  
- Advertising networks  
- Analytics providers  
- External services  

No personal data ever leaves the user’s device except during the official OAuth login handled by Google or Microsoft.

---

## 10. Data Retention and Deletion

Orochi does not store personal data externally, so there is no data to delete.

Users may revoke access at any time:

### Google:
**Google Account → Security → Third-party apps with account access**

### Microsoft:
**Microsoft Account → Privacy Dashboard → Apps and Services**  
(Enterprise users may need to ask their IT administrator.)

---

## 11. Security

Orochi uses:
- HTTPS/TLS encryption  
- OAuth2 secure authentication  
- OS-protected local keychain/token storage  
- No unauthorized data transfers  

OWL Automata follows best practices in software security.

---

## 12. Changes to This Policy

OWL Automata may update this privacy policy as needed.  
The most recent version will always be available at the public privacy URL.

---

## 13. Contact

For questions or privacy requests, contact:

**OWL Automata**  
Email: **info@owl-automata.com**  
Website: **https://owl-automata.com**

---

© 2023–2025 OWL Automata. All rights reserved.
