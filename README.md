# ⚡ SFMC PowerTools — Privacy Policy
 
**Last updated:** October 5, 2026
 
---
 
## Summary
 
SFMC PowerTools does not collect, store, or transmit any personal data. All information stays locally in your browser. No analytics, no tracking, no third-party data sharing.
 
---
 
## 1. What Data We Store
 
SFMC PowerTools stores the following data **locally in your browser** using `chrome.storage.local`:
 
- **SFMC API credentials** — Client ID, Client Secret, subdomain, and optional Account MID, entered by you to connect to your Salesforce Marketing Cloud instance.
- **Cached Data Extension lists** — a local copy of your DE names and keys for faster browsing.
- **Saved SQL queries** — queries you choose to save for reuse.
- **Custom code snippets** — SSJS, AMPscript, or SQL snippets you create.
- **Extension preferences** — your UI settings and star rating.
This data **never leaves your browser**. It is not sent to us or to any third-party server.
 
---
 
## 2. Network Communication
 
The extension communicates directly with the following services:
 
- **Salesforce Marketing Cloud APIs** (`*.marketingcloudapis.com`, `*.exacttarget.com`, `*.salesforce.com`, `*.marketingcloudapps.com`) — to perform the core functionality of the extension: retrieving Data Extensions, running queries, listing automations, etc. These calls go directly from your browser to SFMC's servers using the credentials you provide. No intermediary or proxy is involved.
- **Telegram Bot API** (`api.telegram.org`) — when you click a support/donation button (PayPal or Revolut), a lightweight notification is sent to the developers' Telegram bot. This notification contains **only** the platform name (PayPal or Revolut) and a timestamp. No personal information, no IP address, and no user-identifiable data is included.
---
 
## 3. Data We Do NOT Collect
 
We do not collect, process, or have access to:
 
- Personal identification information (name, email, address)
- Browsing history or web activity
- Your SFMC credentials (they stay in your browser only)
- Any data from your SFMC account (Data Extensions, subscribers, etc.)
- Usage analytics or telemetry
- IP addresses
- Cookies or cross-site tracking
---
 
## 4. Permissions Explained
 
| Permission | Why it's needed |
|---|---|
| `storage` | To save your credentials, cached data, saved queries, and snippets locally in the browser. |
| `activeTab` | To detect when you are on an SFMC page and inject the floating toolbar with page-enhancement features. |
| `notifications` | To display status alerts (e.g., successful import, connection errors). |
| Host permissions | To make direct API calls to SFMC servers and to send donation-click notifications via Telegram. |
 
---
 
## 5. Third-Party Services
 
The extension does not use any third-party analytics, advertising, or tracking services. The only external communication beyond SFMC is the optional Telegram notification described in Section 2.
 
---
 
## 6. Data Security
 
Your SFMC credentials are stored using Chrome's built-in `chrome.storage.local` API, which encrypts data at the browser level. The extension uses OAuth 2.0 Client Credentials flow for authentication with SFMC, and access tokens are refreshed automatically without storing them permanently.
 
---
 
## 7. Data Deletion
 
You can delete all stored data at any time by:
 
- Removing the extension from Chrome (all data is automatically deleted)
- Clearing the extension's storage via Chrome's settings
---
 
## 8. Children's Privacy
 
This extension is a professional tool designed for Salesforce Marketing Cloud administrators and developers. It is not intended for use by children under 13.
 
---
 
## 9. Changes to This Policy
 
If we make changes to this privacy policy, we will update the "Last updated" date above. Continued use of the extension after changes constitutes acceptance of the updated policy.
 
---
 
## 10. Contact
 
For questions or concerns about this privacy policy, contact us at:
 
- Telegram: [@coglia99](https://t.me/coglia99)
---
 
© 2026 SFMC PowerTools — Built by Davide 
