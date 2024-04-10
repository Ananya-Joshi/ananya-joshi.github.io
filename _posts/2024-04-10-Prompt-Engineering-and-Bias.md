---
layout: post
title:  "AutoPrompt: Improving GPT Responses Using Personas and Synthetic Documents"
date:   2024-04-10 
categories: Generative_AI 
---

I spent a few hours using GPT to generate synthetic personas and their relevant documents, and asked the personas to compare their prompt results with one that had context from their documents (AutoPrompt). Here's a quick result from this approach with 79 personas.

![Results from Experiment 1](assets/NLP4.svg)

From this, we had to investigate the possibility of over-fitting to under-represented personas so I ran two experiments to test that overfitting hypothesis over this prototype: 

![Results from Experiment 2](assets/NLP5.svg)

A: For classes of prompts, the baseline GPT response was 17% less satisfactory for underrepresented personas.
B: Using the content of the persona’s documents is 11% more satisfactory than explicit demographic context.

These suggest that adding context from documents may overcome gaps in the underlying baseline of GPT’s recommendation responses (A) but may not be explicitly overfitting to the demographics (B). Some suggested next steps include:
- Regularizing with relevant global context.
- Incorporating real data.
- Testing with a larger sample size.

![Results from Experiment 3](assets/NLP6.svg)

There's definitely a lot of interesting directions going forward here, but these types of synthetic setups enable different types of experiementations than what was historically possible. 

Thank you to Michael Rudow for feedback on the types of prompts and experimental structure!



