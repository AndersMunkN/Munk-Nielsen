---
categories: []
date: 2023-03-23 11:00:00+01:00
draft: false
image:
  caption: # caption if you add a picture 
  focal_point: Left
summary: My thoughts about supervision
tags:
- teaching
title: Supervision
---

# Choosing a topic  

*You can find most of the information from this page in a convenient pdf [here](/pdf/vejledning.pdf).*

**My expertise:** I specialize in empirical or computational research and I am strongest there. I am interested in empirical industrial organization. 

**Choosing a topic:** This is the most important problem. Know that it is ok to have a general interest but not necessarily a specific setting that you want to apply it to. There are, however, some general guidelines. 

1. **Empirical or not:** If you want to work with real data, then the choice of topic is all about the data. Of course there are some datasets that can be used to study many different questions, but for many datasets it is somewhat limited what you can do. 
2. **Know thy self:** Find out what constitutes a good project *for you*. You must be brutally honest about your objectives -- you only deceive yourself otherwise. See 

## Goals 

When writing a thesis, there are some general tradeoffs to consider which determine the best path to follow. For instance, it may sometimes be possible to choose a simpler question to minimize the risk of getting stuck at the cost of a ceiling on how fancy the project can get. 

People differ quite a lot in terms of what matters to them. Therefore, rank the following objectives according to your own preferences.

> **Task:** Rank the following goals according to *your* preferences. 

* **The grade:** Geting it as high as possible. 
* **The process:** A predictable, straightforard process where you constantly know where you are and what the next tasks will be, and how much work is remaining. 
* **Real-world relevance:** Working on a problem, which *matters* to someone in the real world. For instance, solving a problem faced by a firm or public entity right now. 
* **Personal relevance:** Working on a topic that you personally care about. For instance a cause (like saving the environment), a pass-time activity (like a sport or game you enjoy), or an industry you have worked in.
* **Mastery:** Getting the sense of truly *understanding* something at a very deep level, or *building/making* something that you are proud of. 
* **Job prospects:** Learning skills that will make you employable in a specific job type later, which will impress a specific type of employer, or which may be useful in making your own startup. 

## Expectation management

The department of economics allocates a specific number of hours of supervision to each student, more for a master's thesis than a bachelor's thesis. The total time allocated (and this includes for the defense and reading/assessing the thesis) is: 

* Bachelor: 10 hours  
* Master: 25 hours 

Typically, it makes sense to meet every 2-3 weeks, but this changes somewhat with the distance to the deadline. *(Of course, you don't have to worry about keeping track of hours, I will do that. And nobody gets left behind if there is a need for extra supervision.)*

**Your responsibility:** Contact me when you need supervision and we arrange a date. ***Important:*** You must send a calendar invite to my outlook calendar and make sure I accept the invitation so that we are sure we have the same date and time in our calendars. This may be the first time you send an outlook calendar invitation so read up online, there are simple guides [Apple](https://support.apple.com/da-dk/guide/iphone/iph82c5721ca/ios), [Gmail](https://support.google.com/calendar/answer/37161?hl=en&co=GENIE.Platform%3DDesktop), Microsoft, etc. 

**Before a meeting:** Before each meeting, send me 
* A brief agenda with what you want to cover at that meeting. 
* An up-to-date bullet list version of your thesis (see below). 


# Tips

* **Groups:** I recommend working in a group. 
* **Literature search:** Use google scholar. Find a key paper (possibly with my help), then download and read the abstract of every single paper they cite. Next, read the full introduction of the most relevant of those papers, and fully read the 1-3 most relevant of those. 
* **Data work:** When you are struggling, make sure to simplify your problem to the minimal version that reproduces the issue you are struggling with. Don't learn to use Pandas' merge command on two 1GB datasets: use two datasets with 3 rows each, then scale up. This tip may seem simple/stupid, but I promise you that you will ignore it and you will regret ignoring it. Try to minimize the pain you inflict on yourself in this regard. 
* **Know thy self -- getting stuck:** Getting stuck is a part of the process. Learn to understand and identify your own signals. Do you procrastinate with instagram/shopping/netflix/cleaning your apartment? Regardless, know that when you smash your brain against a problem that it cannot solve, your brain will try to rebel against you by procrastinating. It *will* win out eventually, so you *must* give up before you waste too much time. Instead, find a different task you can switch to. For example, make a rule where you switch tasks if you have been stuck with the same problem for over 30min (e.g. go from coding to writing or reading).  



# Bullet list version of your thesis

My experience tells me that the best way to structure the process of writing is by keeping track of a brief bullet list version of your thesis. This list starts out just as the titles of each section. Then as you progress, you can write sub-bullets for each section with the names of the subsections. Then, you can write a third level of bullets with brief keywords for, what you want to cover. Towards the end, you should be able to write a very detailed bullet list that has one keyword for every single page (or maybe even every paragraph). 

**Why?** Because it gives you an overview and it dramatically improves the supervision I can give: it allows me to spot holes/weak points/missing parts early on, so we can avoid last-minute crises where you forget to describe your data the day before handing in. 

## Example: An empirical project

Let's consider an example with a project written using pharmaceutical data. 

> **Research question:** What is the effect of the number of firms on the price.

### First version 

This list can be written the moment you decide on writing an empirical paper. 

1. Introduction: 0%
2. Theory model: 0%
3. Data: 0%
4. Descriptive evidence: 0%
5. Econometric methodology: 0%
6. Results: 0%
7. Discussion: 0%
8. Conclusion: 0%

### Second version 

After getting started with the data, you know more about what the contents should be, but you still haven't written anything or done any of the final results. 

* 1. Introduction: 0%
* 2. Theory model: 0%
* 3. Data: 0%
	* 3.1 The auction dataset 
	* 3.2 The firm dataset 
	* 3.3 Describing the auction mechanism
* 4. Descriptive evidence: 0%
	* 4.1 Summary statistics (table)
	* 4.2 Histograms 
		* 4.2.1 Number of firms 
		* 4.2.2 Bids
	* 4.3 Other plots 
		* 4.3.1 Bids against number of firms 
		* 4.3.2 Number of firms against the size of the municipality 
* 5. Econometric methodology: 0%
	* 5.1 OLS 
	* 5.2 Fixed effects 
* 6. Results: 0% 
	* 6.1 Table: regression results 
* 7. Discussion: 0%
* 8. Conclusion: 0%

### Third version 

Further into the project, you have decided to use estimate the GPV model. This requires explaining the auction model in your theory section and explaining how it can be estimated by quantile regression, as well as explaining quantile regression itself. You will still show OLS and Fixed Effects results as a comparison. 

* 1. Introduction: 0%
* 2. Theory model: 30%
	* 2.1 Standard FPSB auction 
	* 2.2 Heterogeneous bidders 
* 3. Data: 70%
	* 3.1 The auction dataset 
	* 3.2 The firm dataset 
	* 3.3 Describing the auction mechanism
* 4. Descriptive evidence: 80%
	* 4.1 Summary statistics (table)
	* 4.2 Histograms 
		* 4.2.1 Number of firms 
		* 4.2.2 Bids
	* 4.3 Other plots 
		* 4.3.1 Bids against number of firms 
		* 4.3.2 Number of firms against the size of the municipality 
* 5. Econometric methodology: 30%
	* 5.1 OLS: 100%
	* 5.2 Fixed effects: 100%
	* 5.3 GPV: 20% 
		* 5.3.1 The Model 
		* 5.3.2 How to estimate it 
		* 5.3.3 Quantile regression 
* 6. Results: 20% 
	* 6.1 Table: regression results: 100%
	* 6.2 Table: GPV Estimates: 0%
	* 6.3 Table: Robustness checks: 0%
		* 6.3.1 Dropping Southern Denmark 
		* 6.3.2 More flexible specification for (some variable)
* 7. Discussion: 10%
	* 7.1 Weaknesses
		* 7.1.1 Possible omitted variables: 30%
		* 7.1.2 Drawbacks of GPV: 0%
		* 7.1.3 Comparisons with literature: 0%
* 8. Conclusion: 0%

As a supervisor, this gives me immediate insight into where the project is, how much work remains, and whether I think the essential ingredients are there. 
