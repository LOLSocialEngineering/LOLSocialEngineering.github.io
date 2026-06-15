---
Name: Fake Meeting Apps 
Description: Digital collaboration and video conferencing platforms used to host virtual meetings, webinars, and remote teamwork sessions.
Author: Gemini 
Created: 2026-06-15
Techniques:
  - Technique: Malicious Brand Impersonation via Lookalike Domains
    Description: Threat actors host fraudulent landing pages that visually clone popular meeting software portals. The domains use typosquatting or sub-paths specifically structured to mimic legitimate invitation strings (such as mimicking the [a-z]{3}-[a-z]{4}-[a-z]{3} structure of Google Meet links or random Zoom room numbers). Malware delivery varies from email phishing, sometimes with an attachment, urging users to join a meeting to long targeted social engineering campaigns, as observed in the axios supply chain attack. 
    Usecase: Forcing victims to download a malicious installer package or an "urgent software update" script when attempting to join an online conference.
    Category: Technical Coersion 
    MitreID: T1566.002
    Tags:
      - Web: Typosquatting
      - Web: Malicious Payloads
      - Web: Client Impersonation
Examples: 
  - Link: https://cms.zscaler.com/cdn-cgi/image/format=auto/sites/default/files/images/blogs/figure_2_7.png
  - Link: https://cms.zscaler.com/cdn-cgi/image/format=auto/sites/default/files/images/blogs/figure_3_6.png
  - Link: https://www.netskope.com/wp-content/uploads/2026/02/Videoconference-Phishing-3.png 
Safeguards: 
  - Control: DNS Filtering & Lookalike Domain Detection
    Description: Utilize secure DNS web gateways to automatically block access to newly registered domains (NRDs) and domains employing known typosquatting permutations of critical corporate communications tools.
    Link: https://www.zscaler.com/blogs/security-research/android-and-windows-rats-distributed-online-meeting-lures
  - Control: Strict Application Control & Endpoint Containment
    Description: Implement application whitelisting and endpoint protection rules to block the execution of unrecognized automated scripts (such as malicious .bat files) and unauthorized installation of mobile packages (.apk) sourced outside of official app stores.
    Link: https://www.zscaler.com/blogs/security-research/android-and-windows-rats-distributed-online-meeting-lures
Resources: 
  - Link: https://www.zscaler.com/blogs/security-research/android-and-windows-rats-distributed-online-meeting-lures
  - Link: https://cloud.google.com/blog/topics/threat-intelligence/unc1069-targets-cryptocurrency-ai-social-engineering
Acknowledgement: 
  - Person: Zscaler ThreatLabz 
    Handle: '@ThreatLabz'
  - Person: Mandiant (Google Cloud)
    Handle: '@Mandiant'
---
