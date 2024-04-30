---
layout: post
title: "Takeaways from the first InsightNet Meeting"
date:   2024-04-25 
categories: Ph.D. 
---

Last week, I attended the first annual [InsightNet conference](https://insightnet.us/insight-net-annual-meeting-2024/) in North Carolina!

[InsightNet](https://www.cdc.gov/forecast-outbreak-analytics/partners/insightnet/index.html) is a new group of over 100 private, public, and academic collaborators that the CDC has awarded over $100 million of funding to build advanced analytic tools and capacities for disease control. The Delphi Group is one of the [Innovator](https://www.cdc.gov/forecast-outbreak-analytics/partners/insightnet/innovators.html) partners and focuses on method development and public health expert training for modeling! InsightNet's broad priorities include tooling that:
1. Takes advantage of the big data era.
2. Is equitable.
3. Specifies parameters to tailor outputs across settings, especially geography.  

It was great to meet our InsighNet collaborators at the conference, and we had an opportunity to present our poster and get feedback. We're excited to incorporate our collaborator's insights into our work as we build out our tool's volunteering and alert communication pipelines.

![Our Poster Setup](/assets/poster.png) 

Aside from FlaSH, we also got a higher-level overview of the challenges and opportunities that lie ahead for public health experts. My takeaways were: 

**1. Data Concerns Reigned**
Many discussions at the conference tied back to data curation, platforms, authorizations, provenance, and standards, specifically regarding [wastewater data](data.wastewaterscan). These discussions are not unfounded - experts showed how having high quality, fine-scaled data improved vaccination models while also acknowledging that the lack of high-quality data hampers outbreak investigation. As experts affirmed, public health data is incredibly difficult to collect and use for many reasons, including: 

- human behavior data is challenging to obtain and interpret
- data can be incomplete, low-quality, and/or delayed 
- data ownership is not necessarily straightforward  
- there are differences in access to lab testing and data collection processes do not include the entire population
- possibility of overanalysis when data availability does not match historical expectations

**Opportunity:** While there is no shortage of data concerns and an equally large number of proposed data solutions, InsightNet has a unique chance to develop data standards and practices around *tooling*. This could include much needed guidelines on model input parameters and thresholds on data quality/availability, supported platforms, or output/summarization specifications to meet InsightNet's goal #3. This type of guidance can help health departments at all levels "use their data to work for them". I'm looking forward to thinking more about this on the InsightNet Data Standards sub-committee. 

**2. Data Monitoring is Important**
Data monitoring (also known as biosurveillance) is the first application that touches the data before it's used downstream. As Rachel Slayton from the CDC pointed out in her presentation, monitoring is used to estimate the burden of disease, evaluate trends over time, detect emerging infections, and detect outbreaks. This monitoring can support several standard public health applications, including resource allocation, policy recommendations/evaluations, and forecasting. It was great to hear how they, and other organizations, are prioritizing this type of work and how they align with our monitoring methods and goals: 

- **Michigan MICON**: When discussing aberration detection, they noted that an 'eye-test can't always find [aberrations], especially among large data.' It was great to get validation for this phenomenon, which we described in our [IJCAI](https://www.ijcai.org/proceedings/2023/0666.pdf) paper as the basis for the human-in-the-loop framework. They also described the importance of identifying the correct aggregation level for analysis.

![Scale of Monitoring Matters](/assets/scale.png) 

This is why, as we describe in our [AAAI paper](https://ojs.aaai.org/index.php/AAAI/article/view/30222), we consider geospatial hierarchies and evaluate different levels of the data separately. 

- **Clemson DMA Prime**: They discussed how developing a 1) visualization framework for spatiotemporal data analysis that displays outputs from analytical tools and 2) integrating healthcare data into models is worth investigating. We also want to spend more time focusing on this. 
- **EPISTORM** Questions about monitoring can take many forms beyond those I ask in my research. This team discussed formulating problems for developing methods to identify locations that can serve as early disease warnings.

**Research opportunities** for monitoring inspired by these include: 
- preparing data summaries that are relevant to critical analyses
- functions that explicitly incorporate qualitative observations from public health experts 
- identifying patterns across symptom data that indicate new pathogens
- expanding efforts to non-infectious diseases, which would require fundamentally different methods 
- responding to the large fluctuations in available public health data. 

There is a specific opportunity for improving monitoring for rare infectious diseases, like dengue. Right now, public health departments generally monitor human symptoms for dengue. This is a poor indicator as humans are only sometimes tested for mosquito-transmitted diseases (because they are rarer), and symptoms alone may indicate any number of underlying diseases. Determining new methods to identify rare diseases, like dengue, with this type of data is a very tough and interesting research area. 


**3. Trust-building among stakeholders is critical**

Building trust was central to discussions around the future of InsightNet. Two of those relationships in particular need more focus: 

1. Academia x Public Health: Core tensions among these parties included data access requests, lack of meaningful, understandable, or impactful deliverables, and mismatched modeling capabilities and assumptions across the country (some departments have extensive modeling capabilities, while 83% have limited and 53% have no modeling capacity). Building trust requires remaining patient as deeper relationships form between academia and public health. However, to strengthen these connections, academics must take on some projects that can immediately help departments, of which there are many. At the same time, departments need to build procedures to test and iterate on academic research quickly. Extending these collaborations to include healthcare professionals and engineering experts early into the process to deploy simple tools immediately might be a model worth replicating in other InsightNet collaborations.   
2. InsightNet x Public: The folks at InsightNet were highly collaborative, but many described challenges in interacting with their stakeholders, especially the general public. A core insight was building trust outside the panic state in the panic-complacency cycle surrounding public health. Focusing on modeling and technical capacities for non-infectious diseases and communicating these to the general public can increase literacy around modeling caveats and improve interpretations. Toward this goal, one group innovatively collaborated with TV stations to describe their models and predictions. Non-traditional messaging like this have historically been shown to be [impactful](https://pubmed.ncbi.nlm.nih.gov/12285328/) and show promise in improving literacy and trust regarding public health modeling. 

I had a great time learning new public health facts (e.g. Florida's [chicken sentinels](https://www.floridahealth.gov/diseases-and-conditions/mosquito-borne-diseases/_documents/guidebook-chapter-ten.pdf) for dengue) and look forward to future meetings!













