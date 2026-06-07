---
Name: SEO Poisoning
Description: Search Engine Optimization (SEO) poisoning involves manipulating search engine results to make malicious websites appear higher in the rankings, tricking users into clicking on them.
Author: 'Claude'
Created: 2026-06-02
Techniques:
  - Technique: SEO Poisoning
    Description: Search Engine Optimization (SEO) poisoning (also known as search poisoning or malvertising) is a social engineering and initial access tactic where cybercriminals manipulate search engine rankings to place malicious websites at the top of search results for specific keywords. Instead of actively hunting for victims via phishing emails, attackers let the victims come to them. By optimizing fake websites for terms they know users are actively searching for, they exploit the inherent trust people place in search engines like Google, Bing, or Yahoo.
    Usecase: Delivering malware or phishing pages via search results
    Category: Web and Search
    MitreID: T1189
    Tags:
      - Web: SEO Poisoning
      - Web: Malvertising 
Examples: 
  - Link: https://www.crowdstrike.com/content/dam/crowdstrike/www/en-us/wp/2023/05/image1-1024x357.png
  - Link: https://thedfirreport.com/wp-content/uploads/2024/02/19530-002.png
  - Link: https://blackpointcyber.com/nitropack_static/fRYLlNfkAsjjkKzPWlwjVOdnDsFOLVrR/assets/images/optimized/rev-058c0fa/blackpointcyber.com/wp-content/uploads/2025/09/image-16.png
Safeguards:
  - Control: Awareness
    Description: Educate employees on evaluating search results and encourage the use of official sources for software.
    Link: https://blog.knowbe4.com/educate-users-malicious-seo-poisoning-attacks
  - Control: Adblockers
    Description: Install adblockers to remove advertisements from search results.
    Link: https://www.spark.co.nz/online/large-business-govt/why-choose-spark/insights/seo-poisoning-prevention-better-than-cure?srsltid=AfmBOorBFsMN3fh85mqMEblKOeOYKxtMp28O0M6ZP7YlA6qhZQEEOPSM 
Resources:
  - Link: https://www.crowdstrike.com/en-us/cybersecurity-101/social-engineering/seo-poisoning/
  - Link: https://www.microsoft.com/en-us/security/blog/2026/05/26/poisoned-search-results-gpu-mining-cryptojacking-campaign-abusing-screenconnect-microsoft-net-utilities/
  - Link: https://www.huntress.com/cybersecurity-101/topic/seo-poisoning
Acknowledgement: 
  - Person: CrowdStrike
    Handle: '@CrowdStrike'
  - Person: KnowBe4
    Handle: '@KnowBe4'
  - Person: Huntress
    Handle: '@HuntressLabs'
  - Person: SparkNZ
    Handle: '@SparkNZ'
  - Person: Microsoft
    Handle: '@MsftSecIntel'
  - Person: The DFIR Report
    Handle: '@TheDFIRReport'
  - Person: Blackpoint Cyber
    Handle: '@CyberBlackpoint'
---
