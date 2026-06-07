---
Name: FakeCAPTCHA/ClickFix
Description: An attacker uses malicious websites that present fake CAPTCHA challenges, tricking users into clicking on elements that lead to malware downloads or other malicious actions.
Author: 'Claude'
Created: 2026-06-02
Techniques:
  - Technique: ClickFix
    Description: ClickFix is a deceptive social engineering tactic where malicious websites or documents trick users into manually executing code on their own machines. ClickFix exploits human trust by presenting a fake CAPTCHA prompt or fake technical error and giving the user explicit, step-by-step instructions to "fix" it. 
    Usecase: Download information stealers or remote access trojans.
    Category: Web and Search
    MitreID: T1059
    Tags:
      - Web: ClickFix 
Examples: 
  - Link: https://www.microsoft.com/en-us/security/blog/wp-content/uploads/2025/08/Fig5-ClickFix-lure.webp
  - Link: https://www.microsoft.com/en-us/security/blog/wp-content/uploads/2025/08/Fig10-ClickFix-instructions.webp
  - Link: https://www.microsoft.com/en-us/security/blog/wp-content/uploads/2025/08/Fig31-ClickFix-instructions.webp
  - Link: https://www.proofpoint.com/sites/default/files/inline-images/Screenshot%202024-11-14%20at%2012.03.28%E2%80%AFPM.png
Safeguards: 
  - Control: Awareness
    Description: Educate employees on the ClickFix attack flow. Instruct users to never blindly paste "Run" or "Powershell" commands in Windows or "Terminal" commands in Mac.
    Link: https://www.microsoft.com/en-us/security/blog/2025/08/21/think-before-you-clickfix-analyzing-the-clickfix-social-engineering-technique/
  - Control: Disable Win+R Run Dialog
    Description: Use a Group Policy Object or Windows Registry keys to disable the Run dialog window.
    Link: https://mhaggis.github.io/ClickGrab/mitigations.html
Resources: 
  - Link: https://www.microsoft.com/en-us/security/blog/2025/08/21/think-before-you-clickfix-analyzing-the-clickfix-social-engineering-technique/
  - Link: https://www.hhs.gov/sites/default/files/clickfix-attacks-sector-alert-tlpclear.pdf
  - Link: https://www.proofpoint.com/us/blog/threat-insight/security-brief-clickfix-social-engineering-technique-floods-threat-landscape
Acknowledgement: 
  - Person: Microsoft Threat Intelligence 
    Handle: '@MsftSecIntel' 
  - Person: HHS
    Handle: '@HHSGov' 
  - Person: ProofPoint
    Handle: '@proofpoint' 
  - Person: Michael Haag
    Handle: '@M_haggis'
---
