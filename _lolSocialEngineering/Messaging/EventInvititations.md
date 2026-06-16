---
Name: Fake Event Invitation Phishing
Description: A social engineering campaign where attackers send fraudulent party or event invitations via email or SMS to harvest credentials or install remote access malware.
Author: Gemini 
Created: 2026-06-15
Techniques:
  - Technique: Credential Harvesting, Malware Delivery  via Fake Login Portal
    Description: The message impersonates well-known invitation platforms (like Evite or Paperless Post) and directs the user to a spoofed landing page. This page requires the victim to enter their email address and password to "view event details" or "RSVP."
    Usecase: Stealing email account credentials to facilitate further phishing campaigns or identity theft. Malware delivery via download to install remote acceess trojans.
    Category: Phishing 
    MitreID: T1566.002
    Tags:
      - Messaging: Credential Harvesting
      - Web: Impersonation
  - Technique: Malware Delivery via Malicious Installer
    Description: Threat actors have been sending phishing lures impersonating popular evvent invitation platforms like Evite or Paperless Post "inviting" users to a party or event. This technique has been used to send credential harvesting portals to trick users into revealing their email usernames and passwords. More sophisticated campaigns have been observed directing users to open the invitation on a Windows computer, downloading a malicious executable that gives the threat actor full remote access to the machine.
    Usecase: Establishing persistent remote control over the victim's computer for data exfiltration or further exploitation.
    Category: Messaging
    MitreID: T1566.001
    Tags:
      - Messaging: Spearphishing Attachment
      - Malware: RAT
      - Execution: MSI Installer
Examples: 
  - Link: https://www.malwarebytes.com/wp-content/uploads/sites/2/2026/01/image_aa530c.png
  - Link: https://www.malwarebytes.com/wp-content/uploads/sites/2/2026/01/image_ae87d8.png
  - Link: https://www.mcafee.com/blogs/wp-content/uploads/2025/12/Fake-Invite-Phishing.png 
Safeguards: 
  - Control: Multi-Factor Authentication (MFA)
    Description: Enforce MFA on all email and sensitive accounts to prevent unauthorized access even if credentials are stolen.
    Link: https://consumer.ftc.gov/consumer-alerts/2026/05/asked-enter-your-email-address-and-password-open-party-invite-thats-scam
  - Control: Restrict Execution of Installer Files
    Description: Use Group Policy or Endpoint Detection and Response (EDR) tools to block the execution of .msi or .exe files from untrusted sources or temporary folders.
    Link: https://www.malwarebytes.com/blog/threat-intel/2026/02/how-fake-party-invitations-are-being-used-to-install-remote-access-tools
  - Control: Remote Access Tool Monitoring
    Description: Monitor for and alert on the installation of legitimate remote support tools (e.g., ScreenConnect, TeamViewer) that are not managed by IT.
    Link: https://www.malwarebytes.com/blog/threat-intel/2026/02/how-fake-party-invitations-are-being-used-to-install-remote-access-tools
Resources: 
  - Link: https://consumer.ftc.gov/consumer-alerts/2026/05/asked-enter-your-email-address-and-password-open-party-invite-thats-scam
  - Link: https://www.malwarebytes.com/blog/threat-intel/2026/02/how-fake-party-invitations-are-being-used-to-install-remote-access-tools
Acknowledgement: 
  - Person: Malwarebytes
    Handle: '@Malwarebytes'
  - Person: FTC
    Handle: '@FTC'
  - Person: McAfee
    Handle: '@McAfee'
---
