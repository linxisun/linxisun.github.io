---
layout: archive #archive
title: Publications
permalink: /publications/
author_profile: true
---

## Publications & Working Papers

* **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>Patient Triage and Prioritization Under Austere Conditions</q>. _Management Science_, 64(10):4471-4489, 2018. [\[Abstract\]](/abstract/Mass-Casualty-Triage) [\[pdf\]](/files/Sun-Argon-Ziya_Final.pdf) [\[Online Supplement\]](/files/mnsc.2017.2855-sm.pdf) (Former title: Priority scheduling of jobs with unknown types)
* Bin Hu, **Zhankun Sun**, <q>Managing Self-Replicating Innovative Goods</q>. _Management Science, 3rd round review_. [\[Abstract\]](/abstract/MS-Self-Replicating) [\[pdf\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3345311)
* Yutong Li, Ruoqing Zhu, Annie Qu, Han Ye, **Zhankun Sun**, <q>Topic Modeling on Triage Notes with Semi-Orthogonal Non-negative Matrix Factorization</q>. _Journal of the American Statistical Association, minor revision_. [\[Abstract\]](/abstract/ED-Text-Mining) [\[pdf\]](https://arxiv.org/abs/1805.02306)
* Wenhao Li, **Zhankun Sun**, L. Jeff Hong, <q>Who is Next: Patient Prioritization Under Emergency Department Blocking</q>. _Operations Research, in revision_. [\[Abstract\]](/abstract/ED-Who-is-Next) [\[pdf\]](/files/Waiting Time Puzzle.pdf)
* **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>When to Triage in Service Systems with Hidden Customer Class Identities?</q>. _Production and Operations Management, in revision_. [\[Abstract\]](/abstract/When-to-Triage) [\[pdf\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3346173)
<!--
(Former title: Semi-Orthogonal Non-Negative Matrix Factorization with an Application in Text Mining)
-->
* Farzad Zaerpour, Marco Bijvank, **Zhankun Sun**, <q>Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</q>. _Production and Operations Management, in revision_. [\[Abstract\]](/abstract/ED-Physician-Scheduling)

<!--
* Farzad Zaerpour, Marco Bijvank, **Zhankun Sun**, <q>Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</q>. _Production and Operations Management, in revision_. [\[Abstract\]](/abstract/ED-Physician-Scheduling) [\[pdf\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3519625)
-->
* Shuai Hao, **Zhankun Sun**, Yuqian Xu, <q>ED Triage: An Empirical Study of Fast-Track Admission</q>. _Working paper_.
* Cheng Zhu, Beste Kucukyazici, **Zhankun Sun**,  Rick Mah, <q>Design of Specialist Response Policies in Hospital Emergency Departments</q>. _Working paper_.
* Huiyin Ouyang, **Zhankun Sun**, Junyang Wang, <q>Impact of Classification Accuracy for Scheduling Jobs with Unknown Types in Service Systems</q>. _Working paper_.
* Huiyin Ouyang, **Zhankun Sun**, <q>On Scheduling a Two-Class Queue with Concave Waiting Cost</q>. _Working paper_.


## Working in Progress

* <q>Allocation of Intensive Care Unit Beds with Patient Abandonment and Readmission</q>, with H. Ouyang.
* <q>Admission Control under Imperfect Customer Information</q>, with H. Ouyang.
* <q>Priority Scheduling when Job Type Information is not Free</q>, with H. Ouyang.
* <q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>, with H. Ye, et al.

<!---

* <q>Dynamic Appointment Scheduling With Partial Patient Cancellation Information</q>, with Frank Y. Chen, et al.

<ol start="9">
    <li><q>Allocation of Intensive Care Unit Beds with Readmission</q>, with H. Ouyang.</li>
    <li><q>Admission Control under Imperfect Customer Information</q>, with H. Ouyang.</li>
    <li><q>Priority Scheduling when Job Type Information is not Free</q>, with H. Ouyang.</li>
    <li><q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>, with H. Ye, et al.</li>
</ol>
--->

{% if author.googlescholar %}
  You can also find my articles on <u><a href=</q>{{author.googlescholar}}</q>>my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
