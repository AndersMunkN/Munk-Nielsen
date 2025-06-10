---
date: 2025-06-10 
title: Project Management 
summary: How do you plan and structure the largest project of your life so far?
weight: 20 
tags:
- supervision
draft: false
---

# Project Management 

Here are the key stages of thesis writing 

## Empirical project 

An empirical project starts and ends with the data at hand. The data determines what the interesting research  questions are. 

| Stage | Description |
| -- | -- |
| 1. Dataset | Choose a good dataset to work with |
| 2. Preliminary analysis | Load data, conduct simple exploratory analysis to get a feel for the data. |
| 3. Research question | Find out what to analyze | 
| 4. Narrowing down | Find final specification | 
| 5. Write up | Write up the results and discussion |



# A Bullet list version of your thesis

My experience tells me that the best way to structure the process of writing is by keeping track of a brief bullet list version of your thesis. This list starts out just as the titles of each section. Then as you progress, you can write sub-bullets for each section with the names of the subsections. Then, you can write a third level of bullets with brief keywords for, what you want to cover. Towards the end, you should be able to write a very detailed bullet list that has one keyword for every single page (or maybe even every paragraph). 

**Why?** Because it gives you an overview and it dramatically improves the supervision I can give: it allows me to spot holes/weak points/missing parts early on, so we can avoid last-minute crises where you forget to describe your data the day before handing in. 

**Bonus -- AI:** With AI tools, you can use the bullet list to ask the AI to flesh out the text. Then you need to focus on *what* you want to say, and the AI can help you with *how* to say it. 

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
