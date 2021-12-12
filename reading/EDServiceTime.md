---
layout: archive
title: Publications
permalink: /reading/
author_profile: true
---

## What Is Emergency Department Service Time?
> Zhankun Sun

> Department of Management Sciences, College of Business, City University of Hong Kong
> zhankun.sun@cityu.edu.hk

### Abstract


### Introduction

Emergency department (ED) operations are naturally modeled as queueing systems, which requires a good understanding of the demand and service process. Evidences from the existing literature has supported the use of non-stationary Poisson process to model the patient arrival to EDs. However, it remains unclear how to model the service process of patients in the ED.

A distingushing feather of emergency care is that patients return to the same physician multiple times for service.

### Definitions of Service Times
In the literature, different definitions and measures of physician service times have been used.

* Time to disposition (from roomed to disposition decision)
  * This is also the total bed time, right?
* ED length of stay (LOS)
* Pick-to-pick time (P2P time)
* Initial assessment times
* PPH


###### 1. To Batch or Not to Batch? Impact of Admission Batching on Emergency Department Boarding Time and Physician Productivity, by Arshya Feizi, Anita Tucker [\[pdf\]](/files/Tucker_ToBatchorNottoBatch.pdf)

Two productivity measures used in the healthcare operations literature: (1) time to making a disposition decision (akin to discharge rate used in Song et al. 2015); (2) number of patients served (KC et al. 2020)

A good discussion from this paper (they used both the patient volumn from KC et al. 2020 and the throughput time from Song et al. 2015): We use both measures of productivity since they complement each other. Considering only the number of patients served could be misleading because it does not capture _how long_ it took to serve the patients. In other words, serving more patients does not automatically translate to higher patient flow if they are not discharged or admitted in a timely manner. Likewise, considering average shift throughput time, alone, may not necessarily indicate higher productivity since it does not capture the number of patietns on whom the average is generated.

###### 2. The Diseconomies of Queue Pooling: An Empirical Investigation of Emergency Department Length of Stay, by Hummy Song, Anita Tucker [\[pdf\]](/files/The_Diseconomies_of_Queue_Pooling_An_Empirical_Inv.pdf)

What is the measure of physician service time (or productivity)? A patient throughput time, i.e., Disposition time - Roomed time, where disposition time is equivalent to the time of discharge decision for patients who are discharged, and time of bed request for patients who are admitted.

###### 3. Task Selection and Workload: A Focus on Completing Easy Tasks Hurts Performance, by Diwas S. KC, Bradley R. Staats, Maryam Kouchaki, Francesca Gino  [\[pdf\]](/files/ms_2020_KC_task_selection_and_workload.pdf)

Productivity: Total volume of patients discharged by a physician during her shift
