---
layout: post
title: Shiftview, GPT2 for Moral Reframing
date:   2020-09-24 
categories: Moral_Reframing
---

Deploying [the Shiftview repo](https://github.com/Ananya-Joshi/Shiftview-public) on Google Cloud creates a website that highlights my work on ShiftView, an ideological transformer based on the moral foundations theory. You can find a light demo of the work in the sidebar. Please be patient as the translations require time to generate. Additionally, because some of the data is uncensored, there may be cursing and confusing speech. I am not repsonsible for the translations generated. In its current state, ShiftView is simply a guide for what is possible with automated moral reframing.

To get started, click on the left panel and select "Run App" from the dropdown menu.

### Abstract (2019): 

This work proposes a novel ideological transformer tool, called ShiftView, based on the moral reframing concept, by applying natural language processing tools and techniques.

Liberals and conservatives have different morals based on the Moral Foundations Theory [1]. For example, liberals are more likely to base their judgments on the moral value of harm while conservatives may base their judgments on the moral value of purity. Studies have shown that while people can convince others of the same political ideology, they use the same moral rhetoric to convince people with di!erent ideologies, and ultimately fail to do so [2]. Mapping moral rhetoric to match a different ideology is a powerful persuasive tool called moral reframing. This thesis seeks to create ShiftView, an automated ideological transformer using moral reframing.

This project has four parts: generating original datasets from the records of the United States Congress and Twitter, designing a flexible moral classifier using topic modeling, creating a text generator using Recursive Neural Networks and transfer learning, and developing an ideological transformation framework. During the process, several moral reframing methods were prototyped and evaluated. Initial results are reviewed by Amazon Turk Workers. This research is the first step in the multi-year project of automating ideological transform and moral reframing.


[1]Jesse Graham, Jonathan Haidt, and Brian A. Nosek. Liberals and conservatives rely on di!erent sets of moral foundations. 96(5):1029–1046, 2009.
[2] Matthew Feinberg and Robb Willer. The moral roots of environmental attitudes. 24(1):56–62, 2012.

#### July 17, 2020

One inspiring source for Shiftview was [TalkToTransformer](https://talktotransformer.com/?fbclid=IwAR0Hcr977E-xg5gqbtfVqygp0Buo3ULdysJH289jQLJ0PXqnqzE0dPVbxFE) by Adam King. I remember being able to "translate" into different characters from the Lord of the Rings, although it's been a while since I've used it. I tried to re-host ShiftView after it consumed all my free Google Credit hours and began to cost me. As a humble (almost) graduate student, the only reasonable price to me is free hosting. Even with the smallest implementations of ShiftView, the size of the app wouldn't allow it to be a free tier (or decently priced) app simply because the individual models are too big. After hacking the app to its barebones, I couldn't understand why it still cost me so much money. I checked back on TalkToTransformer, only to learn that the site had cost King *$20,000* in what must have been about a year (and is now behind a paywall).

For now, ShiftView is shifting directions, at least for the demo version, until Google or Amazon boosts their free tiers.

### Reflection (2020)

In the past year, there have been many strides in moral foundations research. Some of my assumptions in building ShiftView have been validated, while others have been rejected. With more research in both natural language processing and moral foundations theories, there are many opportunities to refine ShiftView.

I look forward to this challenge and where it takes ShiftView.

### Reflection #2 (2023)

Since 2019, it has become a lot easier to fine tune models and some work in emphasizing ChatGPT's [convincingness](https://link.springer.com/chapter/10.1007/978-3-031-49008-8_34). I'm excited about the developments ahead!  


