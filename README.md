# QuickPhish
QuickPhish is a lightweight, privacy-focused browser extension designed to protect users from phishing attacks in real-time while using web-based email platforms like Gmail and Outlook. Phishing remains one of the top cybersecurity threats, with attackers targeting unsuspecting users through deceptive links embedded in emails. QuickPhish addresses this challenge by integrating seamlessly into the browsing experience and alerting users before they visit a known malicious site.

🔒 Key Features:

Real-Time Link Interception: Detects and intercepts link clicks within Gmail and Outlook interfaces.

Instant Threat Check: Queries a free threat intelligence API (e.g., PhishTank) to determine if the link is known to be malicious.

Warning Modal: If flagged, an in-page warning modal appears to caution the user, giving them a chance to avoid the site.

Lightweight & Fast: Designed with performance in mind, aiming for sub-second detection without noticeable delay or browser slowdowns.

🛠️ Technical Highlights:

Browser Compatibility: Supports Chrome and Edge, using Manifest V3 for modern extension compliance.

No Backend Required: All processing is client-side, preserving user privacy and reducing infrastructure costs.

Focused Scope: Only activates on Gmail and Outlook, reducing resource usage and targeting high-risk contexts.

Modular Design: Includes a standalone threat-detection module, a clean UI component for warnings, and detailed documentation.

🎯 Target Audience:

Corporate Users: Helps reduce phishing-related breaches in enterprise email systems.

Educational Institutions: Offers a teaching tool and protective layer for students and staff.

Security-Conscious Individuals: Empowers users to make safer decisions while using webmail.

📦 Deliverables:

Chrome/Edge-compatible browser extension with full source code.

Integration module for PhishTank or other free threat intelligence sources.

In-page warning UI for malicious URLs.

Installation & usage guide.

Sample phishing email scenario for testing.

Demo video/walkthrough of the extension in action.
