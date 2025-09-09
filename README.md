# PhishShield
AI-powered email security daemon for macOS to detect phishing, malware, and suspicious activity. It is designed for Mac users and can be scaled for businesses.

#Features
- Connects to Gmail, Outlook, or other IMAP/SMPT mailboxes.
- Analyses email headers for SPF, DKIM, and DMARC anomalies.
- Extracts and checks URLs for suspicious domains.
- Scans attachments for risky file types (.exe, .js, macros, etc.).
- AI/ML phishing detection using Higging Face models (for custom rules).
- Logs findings and risk scores.
- Alerts users or moves suspicious emails to a designated folder.
- Modular architecture for easy extension.
