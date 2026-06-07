---
Name: Credential Phishing
Description: Credential phishing is a specific type of cyberattack where attackers attempt to steal sensitive login information—such as usernames, passwords, API keys, or multi-factor authentication (MFA) tokens.
Author: 'Claude'
Created: 2026-06-02
Techniques:
  - Technique: Credential Phishing 
    Description: A link sent in an email that directs the user to a fake login page.
    Usecase: Credential harvesting
    Category: Phishing
    MitreID: T1566
    Tags:
      - Phishing: Phishing 
Examples: 
  - Link: https://consumer.ftc.gov/sites/default/files/netflixscreenshot.jpg
Safeguards: 
  - Control: Awareness
    Description: Educate employees on the common signs of phishing.
    Link: https://www.cisa.gov/secure-our-world/recognize-and-report-phishing
  - Control: Multifactor Authentication (MFA)
    Description: Requires a user to present a combination of two or more credentials to verify a user’s identity for login. 
    Link: https://www.cisa.gov/topics/cybersecurity-best-practices/multifactor-authentication
Resources:
  - Link: https://consumer.ftc.gov/articles/how-recognize-avoid-phishing-scams
Acknowledgement: 
  - Person: FTC
    Handle: '@FTC'
  - Person: CISA
    Handle: '@CISAgov'
---
