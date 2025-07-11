# InsecureBankV2 – Android Mobile Penetration Testing

This project presents a comprehensive penetration test on the Android-based InsecureBankV2 application, conducted as part of a mobile penetration testing final assessment. Each team member focused on specific components mapped to OWASP MASVS/MSTG attack surfaces.

### 🔍 Scope of Assessment
- Insecure Logging of user credentials
- Developer Backdoor allowing auth bypass
- Exploitable Android Content Provider
- Unauthorized activity access via exported components
- Backup functionality abuse and credentials decryption

### ✅ Key Findings
- Sensitive user data such as usernames and passwords were found logged insecurely using `Logcat`.
- A hardcoded backdoor (`/devlogin`) allowed login bypass with any credentials.
- The app exposed its `ContentProvider`, allowing unauthorized query of user data.
- An exported `PostLogin` activity could be launched directly to bypass authentication.
- Backup files included Base64-encoded and AES-encrypted credentials, easily decrypted using a hardcoded key.

Each vulnerability was analyzed using tools such as **JADX**, **Frida**, **Apktool**, and **Android Emulator**, with CVSS v3.1 scores and remediation suggestions provided for every issue.

📄 See the PDF file for the full technical documentation and exploitation steps.
