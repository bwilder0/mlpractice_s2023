# 10-718: Machine Learning in Practice

Instrutor: Bryan Wilder (bwilder@andrew.cmu.edu)

TA: Ananya Joshi (aajoshi@andrew.cmu.edu)

[Syllabus](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/10-718%20syllabus.pdf)

This is a project-based course designed to provide students training and experience in solving real-world problems using machine learning, exploring the interface between research and practice. The goal of this course is to give students exposure to the nuance of applying machine learning to the real-world, where common assumptions (like iid and stationarity) break down. Students will learn how to formulate real-world business or policy scenarios as machine learning problems, how to address common challenges which arise in applying ML to such problems (e.g., distribution shift or missingness), and how to rigorously evaluate the results of such interventions in practice (e.g., through designing randomized trials or observational studies). We will place an emphasis throughout on issues related to ethics and fairness in machine learning, and discuss how choices throughout the machine learning pipeline – including problem formulation, outcome definition, data collection, and model training – contribute to the social impact of algorithmic systems. 

**An overview of the schedule is given below. For a detailed schedule, including readings for each day, see the final section of this page**.

## Course Schedule

| Week | Dates       | Topic                                               | Assignments                                                                                                                                                                    |
|:----:|-------------|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1    | Tu: Jan 17  | [Class Intro and Overview](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture1-ClassOverview.pptx)                            |                                                                                                                                                                                |
| 1    | Th: Jan 19  | [ML Project Scoping](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture2-Scoping.pptx)                                   | Project Team Selection                                                                                                                                                         |
| 2    | Tu: Jan 24  | [Analytical Formulation / Baselines](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture3-Formulation.pptx)                  | Individual Assignment: Getting to know the class project (due Monday)                                                                                                          |
| 2    | Th: Jan 26  | [Model Selection Methodology](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture4-ModelSelection.pptx) |                                                                                                                                                                                |
| 3    | Tu: Jan 31  | [Feature Engineering and Imputation](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture5-Features.pptx)                  | Project Assignment 1: Formulation and Baseline (due Monday)                                                                                                                    |
| 3    | Th: Feb 2   | [Case study session 1](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture6-AdityaMate.pptx)                                | Paper reflection 1 (due before class)                                                                                                                                          |
| 4    | Tu: Feb 7   | [Case study session 2](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture7-hiv.pptx)                                | Paper reflection 2 (due before class)<br>Project Assignment 2:<br>Validation set up<br>Initial pipeline with train and validation set(s) and baseline implemented (due Monday) |
| 4    | Th: Feb 9   | [Imputation + introduction to censored data](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture8-censoring.pptx)  |   **Note: class is virtual today**                                                                                                                                                                             |
| 5    | Tu: Feb 14  | [Human-AI interaction 1](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture9-human-ai-1.pptx)                      | Project Assignment 3:<br>list of features and some subset implemented (due Monday)                                                                                             |
| 5    | Th: Feb 16  | [Human-AI interaction 2](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture10-human-ai-2.pptx)                         | Paper reflection 3 (due before class)                                                                                                                                          |
| 6    | Tu: Feb 21  | Hands on: Review of modeling results                                | Project Assignment 4: <br>modeling results (due Monday)                                                                                                                        |
| 6    | Th: Feb 23  |  [Midterm review + calibration](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture11-calibration.pptx)              |                                                                                                                                                                                |
| 7    | Tu: Feb 28  | Hands on: model debugging and updates               | Updated model results assignment (+ model selection) Due Monday. Takehome midterm available Tuesday                                                                            |
| 7    | Th: Mar 2   | No Class - Extra time for midterm/project work      | Midterm due Fri                                                                                                                                                                |
| 8    | Tu: Mar 7   | No Class - Mid-semester break                       |                                                                                                                                                                                |
| 8    | Th: Mar 9   | No Class - Mid-semester break                       |                                                                                                                                                                                |
| 9    | Tu: Mar 14  | Guest lecture: Fei Fang                                           | Paper reflection 4 (due before class)                                                                                                                                          |
| 9    | Th: Mar 16  | [ML ethics](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture12-ethics.pptx)                                           |                                                                                                                                                                                |
| 10   | Tu: Mar 21  | [Fairness overview](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture13-fairness.pptx)                                   | Paper reflection 5 (due before class)                                                                                                                                          |
| 10   | Th: Mar 23  | Fairness Methods 1                                  |                                                                                                                                                                                |
| 11   | Tu: Mar 28  | Fairness Methods 2                                  |                                                                                                                                                                                |
| 11   | Th: Mar 30  | Fairness Methods 3                                  | Fairness Writeup Due on Friday                                                                                                                                                 |
| 12   | Tu: Apr 4   | [Field Trials and Causal Inference 1](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture14-RCTs1.pptx)                 | Paper reflection 6 (due before class)                                                                                                                                          |
| 12   | Th: Apr 6   | [Field Trials and Causal Inference 2](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture15-causality.pptx)                 |                                                                                                                                                                                |
| 13   | Tu: Apr 11  | [Uncertainty quantification overview](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/Lecture16-UQ.pptx)                 | Paper reflection 7 (due before class)                                                                                                                                          |
| 13   | Th: Apr 13  | No class (Spring Carnival)                         |                                                                                                                                                                                |
| 14   | Tu: Apr 18  | Uncertainty quantification methods 1                        |                                                                                                                                                                                |
| 14   | Th: Apr 20  | Uncertainty quantification methods 2                        |                                                                                                                                                                                |
| 15   | Tu: Apr 25  | Uncertainty quantification methods 3                        |                                                                                                                                                                                |
| 15   | Th: Apr 27  | Wrap-Up                                             | UQ Writeup Due on Friday                                                                                                                                                     |
|      | Finals Week |                                                     | Final Reflection Writeup Due (Date TBD)                                                                                                                                        |

## Detailed schedule and readings

**Tuesday 1/17: Introduction**

---

**Thursday 1/19: Project scoping**

Required Reading:
* Data Science Project Scoping Guide. [Available Online](http://www.datasciencepublicpolicy.org/home/resources/data-science-project-scoping-guide/)

Optional Readings:

* Fine-grained dengue forecasting using telephone triage services by Rehman, NA, et al. Sci. Adv. 2016. [Available Online](https://nyunetworks.github.io/Pubs/rehman-science16.pdf)
* Deconstructing Statistical Questions by Hand, D.J. J. Royal Stat Soc. A 157(3) 1994. [Available Online](http://stat688.bio5.org/sites/default/files/fall2014/hand-deconstructin.pdf)
* Predictive Modeling for Public Health: Preventing Childhood Lead Poisoning by Potash, E, et al. KDD 2015. [Available Online](http://www.dssgfellowship.org/wp-content/uploads/2016/01/p2039-potash.pdf)

---

**Due Friday 1/20: Project groups**  

---

**Due Monday 1/23: Individual Assignment: Getting to know the class project**

---

**Tuesday 1/24: Project formulation and baselines**
 
 Required Readings 

  - *Dissecting Racial Bias in an Algorithm Used to Manage the
    Health of Populations* by Obermeyer, Z., Powers, B., et al.
    Science. 2019. [Available
    Online](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/ObermeyerBias.pdf)

  - *Problem Formulation and Fairness* by Passi and Barocas. FAT\*
    2019. [Available
    Online](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/PassiFormulation.pdf)

Optional Readings:

  - *Always Start with a Stupid Model, No Exceptions* by Ameisen, E.
    Medium. [Available
    Online](https://blog.insightdatascience.com/always-start-with-a-stupid-model-no-exceptions-3a22314b9aaa)

  - *Create a Common-Sense Baseline First* by Ramakrishnan. Medium.
    [Available
    Online](https://towardsdatascience.com/first-create-a-common-sense-baseline-e66dbf8a8a47)

  - *Data Science for Business* by Provost and Fawcett. O’Reilly.
    2013. Chapter 2: Business Problems and Data Science [Available
    Online](https://learning.oreilly.com/library/view/data-science-for/9781449374273/ch02.html)
---
**Thursday 1/26: Model selection and performance metrics**

Required Reading:

  - *Cross-validation strategies for data with temporal, spatial,
    hierarchical, or phylogenetic structure* by Roberts, DR, Bahn,
    V, et al. Ecography 40:2017. [Available
    Online](https://github.com/bwilder0/mlpractice_s2023/blob/main/files/RobertsCV.pdf)

Optional Readings:

  - *Time Series Nested Cross-Validation* by Cochrane, C. Medium.
    [Available
    Online](https://towardsdatascience.com/time-series-nested-cross-validation-76adba623eb9)

  - *The Secrets of Machine Learning* by Rudin, C. and Carlson, D.
    arXiv preprint: 1906.01998. 2019. [Available
    Online](https://arxiv.org/abs/1906.01998)

  - *Big Data and Social Science (2nd edition)* edited by Foster,
    Ghani, et al. Section 7.7 of Chapter 7: Machine Learning. [Available
    Online](https://textbook.coleridgeinitiative.org/chap-ml.html)

---
**Tuesday 1/31: Feature engineering, missing data, and imputation**

Optional Readings:

 - *Missing Data Conundrum* by Akinfaderin, W. Medium. [Available
   Online](https://medium.com/ibm-data-science-experience/missing-data-conundrum-exploration-and-imputation-techniques-9f40abe0fd87)

 - *Feature Engineering for Machine Learning* by Zhang, A. and
   Casari, A. O’Reilly. 2018. Chapter 2: Fancy Tricks with Simple
   Numbers [Available
   Online](https://learning.oreilly.com/library/view/feature-engineering-for/9781491953235/)

 - *Missing-data imputation* by Gelman, A. [Available
   Online](http://www.stat.columbia.edu/~gelman/arm/missing.pdf)
   
---
**Thursday 2/2: Case study on bandits in maternal and child health**

Required reading: Field Study in Deploying Restless Multi-Armed Bandits: Assisting Non-Profits in Improving Maternal and Child Health by Mate et al. [Available Online](https://ai4sibook.org/wp-content/uploads/2022/08/bandits_maternalchildcare-health.pdf)

---
**Tuesday 2/7: Case study on social networks and HIV prevention**

Required reading: AI-augmented interventions for HIV prevention in youth experiencing homelessness by Wilder et al. [Available Online](https://ai4sibook.org/wp-content/uploads/2022/08/HIV_homeless-youth.pdf)

---
**Thursday 2/9: Imputation + censoring and survival analysis**

Class held virtually (link on Slack)

Optional reading: Censoring Issues in Survival Analysis by Leung et al. [Available Online](https://www.annualreviews.org/doi/10.1146/annurev.publhealth.18.1.83)

---
**Tuesday 2/14: Human-AI interaction 1**

Optional reading: Explainable Machine Learning for Public Policy: Use Cases, Gaps, and Research Directions by Amarasinghe, K., et al. arXiv preprint: arxiv/2010.14374 [Available Online](https://arxiv.org/abs/2010.14374)

Optional reading: Optimized Scoring Systems: Toward Trust in Machine Learning for Healthcare and Criminal Justice by Ustun and Rudin. INFORMS Journal on Applied Analytics [Available Online](https://users.cs.duke.edu/~cynthia/docs/WagnerPrizeCurrent.pdf)

---
**Thursday 2/16: Human-AI interaction 2**

Required reading: Effect of Confidence and Explanation on Accuracy and Trust Calibration in AI-Assisted Decision Making by Zhang et al. FAT* 2020. [Available Online](https://arxiv.org/pdf/2001.02114.pdf)

Optional reading: Explainable machine-learning predictions for the prevention of hypoxaemia during surgery by Lundberg et al. Nature Biomedical Engineering 2018. [Available Online](https://www.nature.com/articles/s41551-018-0304-0.pdf)

---
**Tuesday 3/14: Guest Lecture from Fei Fang**

Required reading: AI for Food Rescue by Shi et al. [Available Online](https://ai4sibook.org/wp-content/uploads/2022/08/Food-Rescue.pdf)

---
**Thursday 3/16: ML ethics**

Optional reading: The Fallacy of AI Functionality by Raji et al. [Available Online](https://dl.acm.org/doi/pdf/10.1145/3531146.3533158)

Optional reading: Hidden in Plain Sight — Reconsidering the Use of Race Correction in Clinical Algorithms by Vyas et al. [Available Online](https://www.nejm.org/doi/full/10.1056/NEJMms2004740)


---
**Tuesday 3/21: Fairness introduction**

Required reading: Measurement and Fairness, by Jacobs and Wallach. FAccT 2021. [Available Online](https://arxiv.org/abs/1912.05511)

Optional reading: The Measure and Mismeasure of Fairness by Corbett-Davies and Goel. [Available Online](https://arxiv.org/pdf/1808.00023.pdf)


---
**Tuesday 4/4: Causality and field trials 1**

Required reading: Introduction to Randomized Evaluations, by Gibson and Sautmann. [Available Online](https://www.povertyactionlab.org/resource/introduction-randomized-evaluations)

Optional reading: Randomized Experiments, by Coston, Dulce Rubio, and Kennedy. [Available Online](https://ai4sibook.org/wp-content/uploads/2022/08/randomized-experiments.pdf)

---
**Thursday 4/6: Causality and field trials 2**

Optional reading: Difference-in-Differences, by Zeldow, Hatfield, et al. [Available Online](https://diff.healthpolicydatascience.org/#introduction)

---
**Tuesday 4/11: Uncertainty quantification introduction**

Required reading: Aleatoric and Epistemic Uncertainty in Machine Learning: An Introduction to Concepts and Methods, Sections 1-3, by Hüllermeier and Waegeman. [Available Online](https://arxiv.org/pdf/1910.09457.pdf)



## Fairness and Uncertainty Quantification Modules

Each module will span three class sessions. Within each class session, we will cover 2-3 methods, each of which will be presented by one of the groups. 

* For the day that your group presents, you will give a 20-25 min talk. This talk should present an overview to the class of what problem the method solves and how it works. Then, you should show results from applying this method to your project and discuss the strengths and weaknesses of the method. Accordingly, you must finish implementing this method and analyzing the results by the class session you present in. 

* You may either implement the method from the paper yourself, or use an existing implementation. If you implement the method yourself, comment on what made this process easier or harder (e.g., how complicated is the method to implement? is it numerically stable? does it have a lot of tricky hyperparameters or other decisions in implementation?). If you use an existing implemention, we expect a correspondingly more thorough analysis of the process of applying the method yourself and the results (since you're saving time on the implementation).

* We will release a signup sheet for groups to sign up for methods/times on a first-come-first-serve basis. 

* For each of the sessions that your group does not present in, you should choose one method to implement (no need to sign up, just pick whichever of the methods from that day you like). By the end of the module, each group will have implemented three methods in total (the one that you implement for your presentation plus two more from the other sessions). At the end of the module, your group will produce an extended technical abstract, 4-5 pages in length (using the NeurIPS template) which provides an overview of the three methods you implemented, describes how they were applied in the context of your project, discusses the results of applying these methods, and makes recommendations about the context in which each method may be more or less suitable.  

Each such module contributes 15% of your grade, of which 5% will come from the presentation (clearly presenting the method to the class, implementing it in time for the class session, and discussing your lessons learned) and 10% will come from the writeup. 

One note: many of the questions that we study are only "interesting" if the accuracy of the underlying ML system is reasonably strong but less than 100% (e.g., there may not be fairness concerns about differences in error rates across groups if the system gives the right prediction on every single instance). Depending on your problem formulation and the state of the ML pipeline you've developed, you may consider making the ML problem easier or harder (e.g. by adjusting the amount of time for information to accumulate before making a prediction). 


