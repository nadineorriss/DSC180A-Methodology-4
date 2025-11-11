---
layout: default
title: Methodology Assignment 4
---

**Name:** Nadine Orriss  
**UCSD Email:** norriss@ucsd.edu  
**Section + Mentor:** B08 — Aaron Boussina and Dr. Karandeep Singh

---

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic this quarter was learning how discrete event simulation can model complex hospital systems such as an emergency department. It was rewarding to see how concepts like arrival rates, service times, and routing rules could represent real patient flow and system performance. I also gained a deeper understanding of the limitations of the MIMIC-IV dataset, particularly with timestamp inconsistencies and missing data. My mentors emphasized that missingness is not just noise but information that reflects how the department operates. Learning to interpret missingness as a meaningful part of the data rather than an error taught me to think critically about data quality and the processes it represents.  

---

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For the Quarter 2 Project, I would like to expand our emergency department simulation to evaluate the impact of specific operational interventions. One idea is to test how policies such as provider-in-triage, fast-track implementation, or boarding limits affect key outcomes like length of stay, time to provider, and left-without-being-seen rates. By calibrating the model with real hospital data, the goal would be to identify which strategies most effectively reduce congestion while maintaining patient safety and throughput. This investigation would also explore how differences in arrival patterns and resource allocation influence the overall performance of the emergency department system. The results of this analysis could help guide data-driven staffing and policy decisions across multiple hospital sites.  

---

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
Throughout Quarter 1, I have already begun refining our approach by focusing on event structure, data provenance, and activity sequencing. The most significant shift is integrating UCSD Health data to overcome the limitations of MIMIC-IV, which lacks complete timestamp coverage and full representation of patient flow. By preserving all data initially, documenting table structures, and tracking data loss at each cleaning step, I aim to create a reproducible pipeline for validation and extension. Building an individual patient journey tool and analyzing activity sequences will provide a deeper understanding of variation in care pathways. These changes are intended to carry into Quarter 2, where the simulation will be better grounded in high-quality local data and capable of testing operational interventions with greater accuracy.  

---

**What other techniques would you be interested in using in your project?**  
I would like to incorporate analytical and statistical techniques that strengthen the foundation of the discrete event simulation and support more rigorous evaluation of policy changes. Queueing models could serve as theoretical references for patient flow and help validate the simulated results. Monte Carlo sensitivity analysis would make it possible to test how small changes in arrival rates or service times affect overall outcomes. In addition, Bayesian modeling could allow comparisons across different hospital sites while accounting for uncertainty in the data. These methods would make the simulation more interpretable, reproducible, and aligned with real operational dynamics.  
