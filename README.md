🔐 Task 7 – Browser Extension Security Audit
📌 Objective

To identify and remove potentially harmful or unnecessary browser extensions in order to improve browser security, privacy, and performance.

🖥 Environment

Browser Used: Google Chrome

Operating System: Windows

Audit Method: Manual review of installed extensions and permissions

🔍 Extensions Reviewed
1️⃣ Bookmarks Quick Search (v0.0.16)

Purpose: Quick bookmark search

Permissions reviewed

No excessive or suspicious privileges detected

Status: Retained

2️⃣ Outdoor Photos by Hipcamp (v1.4)

Function: Modifies new tab page

Not essential for daily browsing

Alters browser behavior

Security Decision: Removed to reduce attack surface

3️⃣ Session Buddy – Tab & Bookmark Manager (v4.1.1)

Function: Tab and session management

Requires tab access (expected behavior)

Verified legitimacy through usage and functionality

Status: Retained

4️⃣ Sider – AI Sidebar Extension (v5.25.5)

Function: AI assistant integrated into browser

Requested high-privilege permissions:

Read browsing history

Block content on any page

⚠ Security Concern

These permissions allow the extension to:

Monitor user browsing activity

Modify webpage content

Potentially inject scripts

Access sensitive information if compromised

Even though the extension may be legitimate, high-privilege access increases risk exposure.

Security Decision: Removed to minimize privacy and security risks

🚨 Suspicious / High-Risk Permissions Identified

Read browsing history

Modify or block webpage content

Such permissions can be abused to:

Track user behavior

Steal login credentials

Redirect users to phishing sites

Inject malicious advertisements

Perform cryptomining

🛠 Actions Taken

Reviewed all installed extensions

Analyzed permissions and necessity

Removed non-essential and high-privilege extensions

Restarted browser

Verified stable performance after removal

📸 Evidence

Screenshots included:

Installed extensions (before removal)

High-risk permissions (Sider extension)

Extensions list after removal

🧠 Key Security Learnings

Extensions often request more permissions than required

Unused extensions increase attack surface

High-privilege permissions should always be reviewed carefully

Regular extension audits improve browser security posture

✅ Conclusion

Browser extensions can significantly impact user privacy and system security. Conducting periodic security audits and removing unnecessary or high-permission extensions helps reduce risks and maintain a safer browsing environment.
