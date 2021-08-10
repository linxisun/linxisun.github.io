---
layout: archive #archive
title: Publications
permalink: /publications/
author_profile: true
---

## Journal Publications

1. **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>Patient Triage and Prioritization Under Austere Conditions</q>. _Management Science_, 64(10):4471-4489, 2018. [\[pdf\]](/files/Sun-Argon-Ziya_Final.pdf) [\[e-companion\]](/files/mnsc.2017.2855-sm.pdf) (Former title: Priority scheduling of jobs with unknown types)
1. Bin Hu, **Zhankun Sun**, <q>Managing Self-Replicating Innovative Goods</q>. _Management Science_, 2020. [\[pdf\]](/files/replication_Final.pdf)
1. Yutong Li, Ruoqing Zhu, Annie Qu, Han Ye, **Zhankun Sun**, <q>Topic Modeling on Triage Notes with Semiorthogonal Nonnegative Matrix Factorization</q>. _Journal of the American Statistical Association_, 1-16, 2020. [\[pdf\]](https://arxiv.org/abs/1805.02306)
1. **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>When to Triage in Service Systems with Hidden Customer Class Identities?</q>. _Production and Operations Management_, 2021. [\[pdf\]](/files/Sun-Argon-Ziya-Arrival-POM.pdf)
1. Zhuang Zheng, **Zhankun Sun**, Jia Pan, Xiaowei Luo, <q>An Integrated Smart Home Energy Management Model Based on a Pyramid Taxonomy for Residential Houses with Photovoltaic-Battery Systems</q>. _Applied Energy_, 2021. [\[pdf\]](/files/SHEM_applied_energy.pdf)
6. Wenhao Li, **Zhankun Sun**, L. Jeff Hong, <q>Who Is Next: Patient Prioritization under Emergency Department Blocking</q>. _Operations Research, accepted_, 2021. [\[pdf\]](/files/Waiting_Time_Puzzle_final.pdf)
6. Farzad Zaerpour, Marco Bijvank, Huiyin Ouyang, **Zhankun Sun**, <q>Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</q>. _Production and Operations Management, 3rd round review_. [\[pdf\]](/files/Physician_Rostering_POM.pdf)
6. Shuai Hao, **Zhankun Sun**, Yuqian Xu, <q>Emergency Care Access vs. Quality: An Empirical Analysis of Fast-Track Routing Decisions</q>. _Working paper_.
  * Winner, Best Service Science Student Paper Award, 2020 INFORMS Conference on Service Science.
6. H. Ouyang, **Zhankun Sun**, Junyang Wang, <q>Priority Scheduling When Job Type Information Is Not Free</q>. _Working paper_.
6. Cheng Zhu, Beste Kucukyazici, **Zhankun Sun**,  Rick Mah, <q>Design of Specialist Response Policies in Hospital Emergency Departments</q>. _Working paper_.
7. H. Ouyang, **Zhankun Sun**, <q>Models and Insights from Time-Varying Physician Productivity in Emergency Departments</q>. _Working paper_.


## Medical Publications

* Michele Foster, **Zhankun Sun**, Dongmei Wang, Grant Innes, Laurie-Ann Baker, Andrew McRae, Eddy Lang, <q>Optimal Shift Duration for Emergency Physician Efficiency, Effectiveness and Safety: A Comparison of 6, 7, and 8-hour Shifts</q>. _Canadian Association of Emergency Physicians_. Edmonton, 2015. [\[pdf\]](/files/optimal-shift-duration-for-em-physician-efficiency-foster-abstract-2015.pdf)
* H. Ouyang, Junyan Wang, Zhankun Sun, Eddy Lang, <q>The Impact of Emergency Department Crowding on Admission Decisions and Patient Outcome</q>. _Academic Emergency Medicine_. 2021


{% if author.googlescholar %}
<!---
6. Huiyin Ouyang, **Zhankun Sun**, Junyang Wang, <q>Impact of Classification Accuracy for Scheduling Jobs with Unknown Types in Service Systems</q>. _Working paper_.
## Working in Progress
* Huiyin Ouyang, **Zhankun Sun**, <q>On Scheduling a Two-Class Queue with Concave Waiting Cost</q>. _Working paper_.
* <q>Allocation of Intensive Care Unit Beds with Patient Abandonment and Readmission</q>, with H. Ouyang.
* <q>Admission Control under Imperfect Customer Information</q>, with H. Ouyang.
* <q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>, with H. Ye, et al.

<ol start="9">
    <li><q>Allocation of Intensive Care Unit Beds with Readmission</q>, with H. Ouyang.</li>
    <li><q>Admission Control under Imperfect Customer Information</q>, with H. Ouyang.</li>
    <li><q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>, with H. Ye, et al.</li>
</ol>
--->
  You can also find my articles on <u><a href=</q>{{author.googlescholar}}</q>>my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
