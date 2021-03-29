---
date: "2021-03-27T07:40:51-05:00"
tags: ["Family","Leisure"]
title: "Simplified Research"
draft: FALSE
toc: false
---

My research organization has gotten a little too byzantine over the years. Navigating to an active research project is now *six* levels deep on my computer. If I want to get to my book manuscript, e.g., I have to do the following: `Dropbox/AcademicWork/Projects/Inprogress/mssBook` Then, I still have to navigate within that folder between my archival material, grant reporting, the book proposal, and the manuscript. It's a mess.<!--more--> 

```sh
AcademicWork/Projects/Inprogress

- IRJRF_CCES_2018
	- Accepted_Changes
	- Analysis
	- Data
	- Paper
	- Presentation
	- RnR_Notes
	- RnR_Letter
- Locke_Immg
- Mss_book
	- Archival_Materials
	- Archive_Staged
	- GrantReporting
	- Proposal
	- ResearchMaterials
	- RA_Hiring
	- mss
		- chapter01
		- chapter02
```
In the example above, I included the folder structure for another paper I am working which is in the final stages. Project directories are structured right. [Lincoln Mullen's tutorial](https://kbroman.org/steps2rr/pages/organize.html) recommends keeping all the associated files together. He is not alone. Folders like `data`, `paper`, and `figures` keep things neat and tidy. They especially make things reproducible because they create walls between things like raw data which should never be modified from the sausage of writing a paper. 

The rest needs to be revised. How I got here is somewhat understandable. I got lazy. When I started graduate school, I worked primarily in [Scrivener](https://www.literatureandlatte.com/scrivener/overview), which is still an amazing app, and a pot-pourri of iOS apps on my iPhone (and later iPad). Much of the complexity creep was abated even more (read: ignored) by moving the `Inprogress` folder in my Mac's Finder sidebar. That made getting to an active project one level deep on my Mac and as simple as opening the app I needed to manipulate files on an iOS device. And once I got past my comp exams and started the disseration, I didn't want to change horses midstream.

While writing my dissertation, I noticed an increasing amount of friction. I moved to a plain-text workflow during graduate school. Writing a makefile, e.g., was and is more challenging when the relative path between things is more complicated. Here, too, the complexity can be mitigated (read: ignored) through a clever use of prefixes and shortcuts within makefiles.

```makefile

PREFIX = /Users/lmp/Dropbox/AcademicWork/Pandoc_Templates

BIB = /Users/lmp/Dropbox/AcademicWork/Bibs/refs.bib
BIB2 = /Users/lmp/Dropbox/AcademicWork/Bibs/primary.bib

```

I haven't found a good set of best practices beyond Mullen's tutorial and a few others. It was very helpful to re-read them after a few years. What I need, however, is something beyond mere guidelines and some working examples. In a few weeks I will update what I settled with, but for now, I just want to get a good statement of the problem. 