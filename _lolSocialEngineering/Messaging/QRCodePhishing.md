---
Name: QR Code Phishing
Description: An attacker provides a malicious QR code, often via email or physical media, which when scanned leads the user to a malicious website or triggers an action on their mobile device.
Author: 'Claude'
Created: 2026-06-02
Techniques:
  - Technique: QR Code Phishing
    Description: QR code phishing, also known as quishing, is a social engineering attack where cybercriminals use malicious QR codes to trick victims into visiting credential-harvesting sites or downloading malware. Because traditional email security gateways scan text and links but often overlook images, attackers use QR codes to bypass defenses and land directly in a user's inbox.
    Usecase: Redirecting users to malicious sites via mobile devices
    Category: Phishing
    MitreID: T1566.002
    Tags:
      - Phishing: QR Code Phishing
Examples: 
  - Link: https://unit42.paloaltonetworks.com/wp-content/uploads/2025/03/word-image-317805-138975-1.png
Safeguards: 
  - Control: Awareness
    Description: Educate employees on the common signs of phishing.
    Link: https://www.cisa.gov/secure-our-world/recognize-and-report-phishing
  - Control: 
Resources:
  - Link: https://unit42.paloaltonetworks.com/wp-content/uploads/2025/03/word-image-317805-138975-1.png
Acknowledgement: 
  - Person: Palo Alto Unit 42
    Handle: '@Unit42_Intel'
  - Person: CISA
    Handle: '@CISAgov'
---
