# Digital Forensics – Hashing & File Integrity Lab

This lab explores file integrity verification using MD5 hashing and hex-level manipulation to demonstrate how minor changes in a file can result in completely different hash values. The exercise also highlights the forensic limitations of hash functions and introduces the concept of steganography.

### 🔍 Scope of Work
- Analyzed three identical JPEG images using MD5 hash comparison
- Used HxD Hex Editor to modify a single byte of a file
- Observed how the modified file’s hash differed despite having the same file size and visual content
- Used FTK Imager to examine and export image files from a forensic disk image
- Discussed implications of steganography and the limitations of MD5 for digital fingerprinting

### ✅ Key Observations
- Identical-looking files had **different MD5 hashes**, confirming even a 1-byte change alters the hash.
- Files with the **same size and appearance** may still contain embedded or altered content undetectable without forensic tools.
- Demonstrated how **criminals can exploit JPEG files for steganography**, bypassing casual inspection or surface-level hash checks.

📄 See `Report.pdf` for detailed steps, hash values, screenshots, and forensic insights.
