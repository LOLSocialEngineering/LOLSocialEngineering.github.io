---
Name: Browser Notification Abuse
Description: Attackers exploit browser notification permissions to send frequent, deceptive notifications to users, often mimicking system alerts or security warnings to trick them into visiting malicious sites or downloading malware.
Author: 'Claude'
Created: 2026-06-02
Techniques:
  - Technique: Browser Notification Abuse
    Description: Browser notification abuse (also known as "notification spam" or "malicious web push notifications") is a technique where malicious or rogue websites exploit the HTML5 Web Notification API to flood a user’s desktop or mobile device with spam, deceptive advertisements, and phishing alerts.
    Usecase: Driving traffic to malicious websites or phishing pages
    Category: Technical Coercion
    MitreID: T1204.001
    Tags:
      - Coercion: Browser Notification Abuse 
Examples: 
  - Link: https://www.malwarebytes.com/wp-content/uploads/sites/2/2025/11/image_a53673.jpg
Safeguards: 
  - Control: Turn off browser notifications
    Description: Find and remove unwanted browser notifications
    Link: https://www.malwarebytes.com/blog/news/2025/11/matrix-push-c2-abuses-browser-notifications-to-deliver-phishing-and-malware
Resources: 
  - Link: https://www.malwarebytes.com/blog/news/2025/11/matrix-push-c2-abuses-browser-notifications-to-deliver-phishing-and-malware
Acknowledgement: 
  - Person: Malwarebytes
    Handle: '@Malwarebytes'
---
