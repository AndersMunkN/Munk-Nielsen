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

1. **Empirical or not:** If you want to work with real data, then the choice of topic is all about the data. Of course there are some datasets that can be used to study many different questions, but for many datasets it is somewhat limited what you can do. Here's an excellent resource for finding papers that can be *replicated*, which typically means that there is both data and code accompanying: [uni-goettingen.de](https://replication.uni-goettingen.de/wiki/index.php/Category:Replication). 
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

## Examples

* **A high grade:** Focus on a project that allows you to use a technically sophisticated tool that is (slightly) beyond what gets taught in the more advanced courses (in a meaningful way). If working empirically, make sure the dataset is easy to use, since the marginal benefits to the grade from raw data cleaning work start to diminish quickly. A mathematically or computationally sophisticated method typically involves a lot of hard but predictable work and will look flashy regardless of whether it makes a huge difference in practice. 
* **A good process:** Focus on an existing paper and re-trace their steps. For empirical projects, finding a paper that is published in a great journal and has replication data is ideal. Then for the first 80-90% of your thesis work, your goal is simply to replicate everything they have done, while you blindly trust that at the end of all this work, you will have thought of a brilliant extension / alternative specification / alteration of the key outcome / different policy counterfactual, which will set you apart. 


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

## Dos and don'ts

| In terms of ... | don't | instead do | 
| -- | -- | -- | 
| Literature | Rely on a single paper | Rely on many papers | 
| Arguments | *"Clearly, X should lead to Y"* | *"Johnson (2023) argues that X leads to Y."* | 
| Writing | Start writing | First make a bullet list of what you plan to say | 

## Writing 

* Each page of text should contain 3-5 paragraphs. And each paragraph should be concerned with one *thing*. Make sure the first sentence in the paragraph clearly outlines this. (See more below.)
* Your introduction should state your **research question**, preferably highlighted (in italics or bold font). See below

### How to structure a paragraph of text 

The first sentence should inform the reader what the paragraph is about as well as why it is logically placed where it is. Here are two examples that have the same *contents* but present them differently. 

1. **Don't:** *Table Y shows a different set of results. These results are very similar to those in Table X. They are based on a different specification with fixed effects at the firm level. Such fixed effects control for time-invariant confounders, meaning that the results in Table Y are more robust than those in Table X. In this sense, by comparing the two tables, we may conclude that time-invariant confounders are unlikely to be a major issue.* 
2. **Do:** *A natural critique of the results in Table X is whether there could be any omitted variables. To address this, Table Y presents the results from a specification with firm fixed effects. These fixed effects control for any time-constant omitted confounders that might otherwise bias my results. As is evident, the results are extremely similar, so I conclude that time-constant confounders cannot be a major issue.* 
* In 1, the first sentence gives no indication of the *logic* behind how table Y relates to table X. It is as if the paragraph is just a part of a long list: *Table X shows this; Table Y shows that; Table Z shows this.* It is exceedingly tiresome to read text like this since the reader is not given any guidance as to the thought process behind why the author has chosen those three tables, nor how they relate to each other. Those thoughts become clear only by reading the full paragraph and stepping back and thinking *oh that's why Table Y comes after Table X*. Always give the reader this crucial guideline *before* and not *after* presenting the long convoluted analysis. 
* **What 2 does:** The reader is able to skip the entire paragraph without losing track of the narrative arc. If all the thesis is written like this, it is possible to understand what happens by always reading only the first sentence. Then, if the reader is feeling curious or disagrees, she will choose when to wake up and engage and fully concentrate on the contents of a particular paragraph. 

### The research question 

The single hardest thing in a good thesis is the **research question**. It is not possible to write this in its final form before after the thesis is fully written. But it very much is possible to write it in a broader form at the start of the work and then refine the question as you narrow in on what specifically you want to investigate. 

It is very difficult but very important to work very hard on the research question. When you hand in, you should ideally have had 30 different versions of the research question as you experiment and zoom in. Tiny seemingly inoccuous differences in how you phrase your question can make or break a good question. A good question should 

* Be focused around a **tradeoff** 
	* E.g.: *What's the optimal fuel tax that balances consumer welfare against climate change?* 
	* A good question has rich arguments for prioritizing both sides of the equation 
* Hint at the **policy question** (i.e. who the issue matters for?)
	* E.g. *How can we design markets to mitigate the anti-competitive effects of pricing algorithms?* (implicitly, the policy maker is the market designer)
* Motivate *all* of your thesis
	* If you have two key *things* you want to study, then your question must be sufficiently broad that it cannot be answered without addressing both *things*. 
	* This will also force you to think carefully about why you need both things in your thesis and help you avoid the following thesis structuer: *In the following, I will cover 7 unrelated regressions that I chose to run in order they occurred to me. All are interesting in their own regard.* 
* Be as **precise** (and thereby **narrow**) as possible

# Project Management: Bullet list version of your thesis

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

# The Defense 

## What happens 

| Activity              | Bachelor | Master | 
| --------------------- | -------- | ------ | 
| Student presentation  | 10-12min | 20-25min | 
| Discussion   			| 13-15min | 30-35min | 
| Grading 				| 5min 	   | 5min 	  | 
| **Total** 		    | **30min** | **60min** | 


## The student presentation 

* **Slides?** Most students choose to use slides (a projector or screen will be available in the room), although it is not a requirement. 
* **Language:** You must defend in the same language as you wrote your thesis in (which is the language you signed up for). I have never experienced that the English proficiency of a student affected the final grade (and I have heard some relatively bad English!). The exam is a test of your skills in economics, not in English; and we are perfectly able to distinguish the two. 
* **What to talk about?** Generally, make sure to focus on the big picture and the overall narrative arc in your thesis. Do not worry about mentioning all tiny technical twists or reservations, we have just read the thesis and have everything fresh in memory. The presentation is a great way of showing the external examiner (and your supervisor) the brilliant structure behind your work: a simple yet important research question; the right method to examine the question; perhaps a great dataset; a rich analysis; and a clear message. 
* **Questions?** Typically, there will be no questions during the student presentation, although there may be qualifying questions. 

## Discussion 

* **Who leads?** Typically, the supervisor has questions for guiding the discussion. 
* **In doubt? Ask!!** It's ***perfectly acceptable*** to ask questions like 
	* *"It sounds like you're asking if XYZ, am I hearing you right?"*
	* *"I'm not sure I follow, could you reformulate your question?"*
	* *"Do you want me to give an example or to talk about the math?"*
	* And it is fine to ask twice. 
	* It costs you *nothing* to ask these clarifying questions where you try to ensure agreement about the contents of the question. Of course you should not ask if you are not in doubt, but you should _not_ feel like you have to say anything. 
	* Typically, there's something that confuses you or something you suspect the question is about. If so, add it, e.g. *"It sounds like you're asking about the results of XYZ, but then I don't follow what you mean about including ABC?"*
* **Nervous?** Everybody gets nervous. But it's typically only yourself who is aware of it. There are many strategies for dealing with nerves, take the opportunity to learn about yourself and think about what works for you. Some suggestions: 
	* The stakes are not as high as you may be worried about: remember that the majority of the grade is based on your written thesis, not the last 0.5-1 hour of work. The oral examination is mainly there to ensure that one could not get someone else to write the thesis without doing any work oneself. 
	* Talk about it: It's perfectly fine to say *"I'm feeling a little nervous today"*. Nobody will think any less of you!!! But it will give your supervisor an important cue to help facilitate a good discussion with empathy and an inviting posture. You can also bring this up with your supervisor before. If you have any triggers (harsh words, not shaking hands with the external examiner first, being interrupted, etc.), be sure to mention them. 
