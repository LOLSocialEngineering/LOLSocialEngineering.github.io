---
Name: Callback Phishing
Description: Shifting the payload delivery phase from the digital email channel to a live voice interaction, drastically reducing the tactical indicators available to standard security gateways.
Author: Gemini 
Created: 2026-06-10
Techniques:
  - Technique: Callback Phishing 
    Description: Callback phishing, also known as Telephone-Oriented Attack Delivery (TOAD) hybrid attack strategy where an adversary sends a technically "clean" email lacking malicious links to successfully evade automated filters. The email relies entirely on an urgent pretext (e.g., a fraudulent subscription invoice, a notice of a faked corporate breach) to pressure the recipient into calling a provided customer support or security audit telephone number. Once the victim places the call, a live threat actor socially engineers them into installing Remote Administration Tools (RATs) or yielding corporate credentials.
    Usecase: Bypassing Secure Email Gateways (SEGs) and executing post-exploitation steps via direct user manipulation.
    Category: Phishing
    MitreID: T1566.004
    Tags:
      - Web: vishing
      - Web: hybrid-phishing
      - Web: toad
Examples:
  - Link: https://cdn.prod.website-files.com/68d0d3deea83674e59bf4046/68d26117e3d2ba8cd714af58_673b63c3fe2590ac9f843d83_64f8d9aa0035c0ba3718ec90_pzLKB5Y_NbRxv9AOLwCMrMRDhgniyT6bkTK1TO-39jsUOQ5fn2yj4_V4J5x67hWpqLx2xVg6ymnh7tqPq3727fd3dpQiWtisSqoQFNyMU8MfC_59CYb3hIbXQuVx-P9_CpLyxT4ClAvles7b4rnZcf8.png
  - Link: https://it.brown.edu/sites/default/files/pbowl_geeksquad16_inv.jpg
  - Link: https://www.bleepstatic.com/images/news/security/phishing/a/apple/apple-account-callback-phishing/apple-account-callback-phishing.jpg
Safeguards:
  - Control: Behavioral AI & Intent Analysis
    Description: Deploying advanced email security solutions capable of natural language processing (NLP) to detect invoice fraud, financial urgency, and phone numbers acting as the exclusive call-to-action, alongside OCR scanning for numbers embedded in image/PDF attachments.
    Link: https://abnormal.ai/blog/toad-attacks-phone-phishing
  - Control: Out-of-Band Verification Protocols
    Description: Implementing strict organizational awareness training teaching employees to completely bypass phone numbers listed in unexpected billing alerts, forcing verification through pre-established, independent vendor portals.
    Link: https://ironscales.com/glossary/callback-phishing
Resources:
  - Link: https://www.crowdstrike.com/en-us/blog/callback-malware-campaigns-impersonate-crowdstrike-and-other-cybersecurity-companies/
  - Link: https://ironscales.com/glossary/callback-phishing
  - Link: https://abnormal.ai/blog/toad-attacks-phone-phishing
Acknowledgement:
  - Person: Abnormal AI
    Handle: '@Abnormal'
  - Person: CrowdStrike Intelligence
    Handle: '@CrowdStrike'
  - Person: IRONSCALES
    Handle: '@IRONSCALES'
---
