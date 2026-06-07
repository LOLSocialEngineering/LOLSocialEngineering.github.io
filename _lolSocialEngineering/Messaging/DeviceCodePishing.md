---
Name: Device Code Phishing
Description: An attacker tricks a user into providing a device code, typically obtained through a legitimate Microsoft service, to gain unauthorized access to the user's account.
Author: 'Claude'
Created: 2026-06-02
Techniques:
  - Technique: Device Code Phishing
    Description: Attacker sends the victim a phishing email with a malicious attachment or link requesting a alphanumeric code to view the contents. Entering the code on attacker infrastructure initiates OAuth Device Authorization Grant flow, giving the attacker a session token with the user's permissions.
    Usecase: Account Compromise
    Category: Phishing
    MitreID: T1566.003
    Tags:
      - Phishing: Device Code Phishing 
Examples: 
  - Link: https://cdn.builder.io/api/v1/image/assets%2F3eb6f92aedf74f109c7b4b0897ec39a8%2F27e82099aae94ab587f15c61c79b688c?width=1200&format=webp&quality=85
  - Link: https://www.microsoft.com/en-us/security/blog/wp-content/uploads/2026/04/image-3.webp
Safeguards:
  - Control: Awareness 
    Description: Educate employees on the common signs of phishing.
    Link: https://www.cisa.gov/secure-our-world/recognize-and-report-phishing
  - Control: Conditional Access Policy
    Description: Only allow device code flow where necessary.
    Link: https://www.microsoft.com/en-us/security/blog/2026/04/06/ai-enabled-device-code-phishing-campaign-april-2026/ 
Resources:
  - Link: https://www.huntress.com/blog/oh-auth-2-0-device-code-phishing-in-google-cloud-and-azure
  - Link: https://www.huntress.com/resources/what-is-device-code-phishing
  - Link: https://www.microsoft.com/en-us/security/blog/2026/04/06/ai-enabled-device-code-phishing-campaign-april-2026/
Acknowledgement:
  - Person: Huntress
    Handle: '@HuntressLabs'
  - Person: Microsoft
    Handle: '@MsftSecIntel'
  - Person: CISA
    Handle: '@CISAgov'
---
