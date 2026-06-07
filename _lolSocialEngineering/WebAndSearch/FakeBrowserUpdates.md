---
Name: Fake Browser Updates 
Description: Fake browser update campaigns convince users that their web browser is outdated and insecure, forcing them to manually download and execute the payload.
Author: 'Claude and Friends'
Created: 2026-06-02
Techniques:
  - Technique: Fake Browser Updates
    Description: Attackers do not typically build these malicious websites from scratch. Instead, they compromise legitimate, high-traffic websites (such as blogs, news sites, or small business pages) by exploiting vulnerabilities in content management systems (like WordPress) or plugins. Once inside, they inject malicious JavaScript into the site’s source code. When a user visits the compromised site, the injected script analyzes the visitor's traffic (checking their user-agent, IP address, and location). If the visitor meets the attacker's criteria, the script completely overlays the legitimate website with a highly realistic, full-screen fake update prompt.
    Usecase: Download and install information stealers, remote access trojans, or remote monitoring software.
    Category: Web and Search
    MitreID: T1189
    Tags:
      - Web: Fake Browser Updatesi
      - Web: Fake Updates
Examples: 
  - Link: https://lh3.googleusercontent.com/Opsb7huiddG8az9vN9rF6Ds0I_QLsJpd_VVQfjElnB9hZNQxnDwO21YJBloBq8YAs4OB=w673 
  - Link: https://www.silentpush.com/wp-content/uploads/image-11-1.png
  - Link: https://pbs.twimg.com/media/GYuybA4W0AAOpn9?format=jpg&name=large
  - Link: https://www.bleepstatic.com/images/news/malware/w/warmcookie/fakeupdate/fake-microsoft-edge-update.jpg
Safeguards: 
  - Control: Awareness 
    Description: Ensure employees do not run updates themselves and if required, request help from IT. Understand that most modern browsers are automatically updated.
    Link:  https://it.ucsf.edu/feb-2026-fake-browser-update-attack
  - Control: Application Whitelisting/Allowlisting
    Description: Use Windows Defender Application Control (WDAC) or an EDR to whitelist approved applications in your environment.
    Link: https://www.crowdstrike.com/en-us/cybersecurity-101/observability/application-whitelisting/
Resources: 
  - Link: https://www.proofpoint.com/us/blog/threat-insight/are-you-sure-your-browser-date-current-landscape-fake-browser-updates
  - Link: https://x.com/GenThreatLabs/status/1840762181668741130
  - Link: https://www.silentpush.com/blog/drivesurge/#Analyzing-an-Obfuscated-Payload-Leads-to-macOS-Malware 
Acknowledgement: 
  - Person: SilentPush
    Handle: '@silentpush'
  - Person: GenThreatLabs
    Handle: '@GenThreatLabs'
  - Person: BleepingComputer
    Handle: '@BleepinComputer'
  - Person: Proofpoint
    Handle: '@proofpoint'
  - Person: UCSF IT
    Handle: '@ucsf'
---
