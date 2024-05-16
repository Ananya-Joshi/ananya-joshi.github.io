---
layout: post
title:  "Comments on CMS proposed rule (CMS-1808-P)"
date:   2024-05-16 
categories: Ph.D. 
---

The CMS proposed rule will impact how data related to public health will be collected. Two standout quotes related to monitoring large-scale systems are,

1. “The CDC will continue increasing the automation capabilities of the surveillance systems like NHSN.”, which is the National Healthcare Safety Network (NHSN). NHSN has guidelines for internal validation at the facility level before data is sent to the national repository, as well as external validation for data completeness and accuracy (Validation Resources [here](https://www.cdc.gov/nhsn/validation/2023.html).  

2. “Every day, more than 2000 users (analysts at all levels of government)... conduct 4000 searches of data” using the National Syndromic Surveillance Program ([NSSP](https://www.cdc.gov/nssp/index.html)). Clearly, monitoring public health data is an essential function and efforts to improve this process are well motivated. 

Here were my opinions on the rule that I submitted as a comment: 

The section "Requirements for Hospitals and CAHs to Report Acute Respiratory Illnesses" ensures consistent access to high-quality healthcare data, which is crucial for designing effective preventive and mitigation strategies. 

**1. Non-Emergency Data Requirements are Critical:** Establishing standard data access during non-emergency periods is vital for: 
	a. Facilitating Robust Preventive Measures: Public health surveillance systems can detect changes in this data that may indicate larger-scale systemic issues or disease dynamics [1]. Early detection allows public health experts to prepare for future emergencies. 
	b. Providing Essential Context During Emergencies: Consistent historical data helps decision-makers understand the biases in measurement data, allowing for better calibration of new observations during public health emergencies. 
	c. Refining Tools and Models: Adequate time for modeling and tooling staff to iterate on public health decisions ensures that these tools are trusted and their outputs are interpreted responsibly during emergencies. 

**2. Additional Data Features Support Emergency Response:** For many tooling applications, important data requirements, in order of importance, are 1) the available history, 2) additional features, especially age, and 3) line-level data. Adding additional data features beyond age (like SDOH) during emergency periods can provide greater insight into disease dynamics and support intervention capacities. For example, in some public health decision support tools [2], access to daily, line-level data stratified by demographic was critical in identifying and mitigating bias. Other features to consider are the length of average hospital bed stay and average resource utilization beyond beds.

Implications: Setting up this consistent data infrastructure is a critical investment for long-term health outcomes and would pay back many more times in reduced healthcare costs. Platforms like Abridge, which convert patient conversation into fully drafted after-visit documentation, can be extended to a broader set of clinical documentation tasks and reduce the frequency of errors. Reporting organizations should use this transition time to test, inspect, and revamp their deployed data pipelines, as broken pipelines may be challenging to identify and correct later. 

[1] Chen, Hsinchun, Daniel Zeng, and Ping Yan. Infectious disease informatics: syndromic surveillance for public health and biodefense. Vol. 21. New York: Springer, 2010.   
[2] Joshi, Ananya, Chris Scott and Roni Rosenfeld. Cases2Beds: A Case Study in Actionable Intelligence. https://delphi.cmu.edu   
