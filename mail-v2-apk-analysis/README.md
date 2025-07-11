# Competitor Mail V2 – APK Analysis & Exploit Evaluation

This project was conducted as part of a mobile penetration testing final exam. The objective was to analyze and evaluate the security of a competitor’s Android mail application using static and dynamic techniques.

### 🔍 Scope of Assessment
- Rooted Device and Emulator Detection (bypass attempt)
- Message Duplication via Email Function
- SharedPreferences Data Exposure
- Intent Forgery via LocalBroadcastManager

### ✅ Key Findings
- **Root Detection**: App uses RootBeer for checking rooted devices; analysis of `RootCheckService` and `EmulatorCheckService` conducted. Frida instrumentation was attempted but resulted in runtime errors.
- **Other Features**: Email message duplication, SharedPreferences access, and forged Intent injection were analyzed and determined **not exploitable** based on code behavior and limitations.

The report includes technical steps using tools like **JADX**, **Frida**, and **Android Emulator**, as well as annotated screenshots and method analysis.

📄 See the PDF file for the full assessment and technical evidence.
