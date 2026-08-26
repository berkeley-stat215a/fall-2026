---
title: "Syllabus"
---

# Syllabus

**Instructor:** Professor Bin Yu, binyu@berkeley.edu
**Lectures:** T/Th: 11 am - 12:30 pm (Gateway B1026)

**Office hours (on-line):** T: 10-11 am; Th: 12:30-1:30 pm
[https://berkeley.zoom.us/j/2496506181](https://berkeley.zoom.us/j/2496506181)

**Discussion:** Friday: 9:00 am - 11:00 am (Gateway B1026)

**GSIs and office hours:**
Anqi Wang (aqwang@berkeley.edu) — Office Hours: Weekly Tu 9:30-11 am (starting Tue Sep. 1); Weekly W 11 am-12:30 pm (starting Wed Sep. 2). Nico Sanchez (nicolas_sanchez_ep@berkeley.edu) — Office Hours: TBA. GSIs will be in charge of the discussion sessions, Ed Discussions, and the labs/homeworks.

---

**Text books:**
* "Veridical data science: the practice of responsible data analysis and decision-making" by Bin Yu and Rebecca Barter (free on-line version at [vdsbook.com](https://vdsbook.com); print version by MIT Press at [https://mitpress.mit.edu/9780262049191/veridical-data-science/](https://mitpress.mit.edu/9780262049191/veridical-data-science/)) (required).
* Statistical models, David Freedman (Cambridge Press, 2009, 2nd Ed.) (required).
* The elements of statistical learning, Trevor Hastie, Rob Tibshirani, Jerome Friedman (Springer, 2016, 2nd Ed.) (recommended).

---

**Comments, Suggestions, Gripes:** Before or after the lectures, email, or talk to the instructor and the GSI.

---

**Ed Discussion:** Questions and discussion about course material, HWs, and labs can be posted on the Ed Discussion page (accessed on bCourses). The GSI will regularly monitor this to ensure all questions are answered in a timely manner, but students are encouraged to help their classmates as well. Please think carefully before asking questions specifically about the projects. For example, questions concerning how to do something specific in Python are fine, but questions asking what other people did for their analysis are not. Questions asking about clarifications are fine.

---

**bCourses:** [https://bcourses.berkeley.edu/courses/1557795](https://bcourses.berkeley.edu/courses/1557795)

**Course website:** [https://stat215a.berkeley.edu/fall-2026/](https://stat215a.berkeley.edu/fall-2026/)

---

**Grading:**
* 55% assignments (homework and labs)
* 5% class/discussion participation and reading assignments
* 15% midterm
* 25% final project

---

**Assignments:**
There will be 4 or 5 assignments given out on Friday in the discussion session and usually due in two weeks (there will be an announcement if otherwise). **The assignments require two full weeks of work to satisfactorily complete, which requires a very early start.** The assignments contain homework problems and data analysis labs. For the data labs, each student will produce a 12-page (maximum) report presenting a narrative that connects the motivating questions, the analysis conducted and the conclusions drawn. The labs will be completed in Python (optionally some parts in R, especially for visualization). The reports will be made using Jupyter Notebooks or pure LaTeX and the final pdf output should not contain any code whatsoever. Each report will be hosted in a Github repository containing both the code and the written report, and an automated script will pull the submissions at 12:00am on the due date (i.e., at the end of the due date day). HW submissions will be made to Gradescope. **No late assignments** will be accepted, *for any reason.*

---

**Readings:**
There will be a number of readings assigned throughout the semester. The assigned readings for each week and links to the papers can be found in the calendar on the course website. Students should read at least one paper carefully and go through other readings (as time allows) each week and be prepared to discuss their takeaways during the lecture and lab.

---

**Gradescope:** [https://www.gradescope.com/courses/1368718](https://www.gradescope.com/courses/1368718) (via bCourses, Entry Code: 3ZG3KY)

---

**Course description:**

**Overview**

We live in an age of **Artificial Intelligence (AI)** powered by data-driven algorithms. More accessible large-scale data, combined with **Machine Learning (ML)** tools, are enabling scientists to accelerate drug discovery, social scientists to understand complex societal dynamics, and government agencies to more efficiently allocate resources. **Generative AI** specifically is transforming content creation and communication. From improving personalized medicine to developing autonomous systems, these data-driven methods are addressing increasingly sensitive and complex questions in society, necessitating a strong focus on their **robustness, safety, reliability, and ethical implications.**

Having data alone, even high-quality, is not enough for problem solving and knowledge generation. To be able to solve a domain problem or answer a domain question, it takes a principled statistical and machine learning based investigation process in the context of and in combination with domain knowledge. This process includes problem formulation in context and with a domain goal outside of statistics, data collection (ideally through careful experimental design), data cleaning, data visualization, algorithm/model development, validation, post-hoc analysis, and drawing conclusions in context. It rests on adequate domain knowledge, suitable computing platforms, appropriate choices of data cleaning schemes and scalable algorithms/models, and careful consideration of domain knowledge and information from the data to draw meaningful conclusions about a domain problem. That is, with both computation and narratives (domain knowledge) forming its foundation, the statistical and machine learning investigation process is one of rigorous evidence-seeking to make trustworthy data-driven conclusions that are useful for the domain problem and accessible by the domain experts.

The most impactful contributions are often made when domain experts (scientists, for example) and statisticians and machine learners work together to brainstorm and ask questions. These domain experts are not only key to formalizing the ideas, but they also are integral in generating the data. Engaging with the individuals who collected the data in the first place allows the statistician and machine learner to learn about the context in which the data lives, and subsequently, to conduct an effective analysis capable of answering the question being asked.

---

**Collaborative learning in context** This course will demonstrate what it is like to be an applied statistician, or data scientist in today's data-rich world. We emphasize the goal of answering questions outside of statistics or machine learning using data and domain knowledge through working with domain experts. We illustrate through lectures, class discussions, data labs, and homework assignments, the many steps involved in the iterative process of information extraction and evidence gathering of a statistical investigation. Specifically, students will learn together and critically understand the technical topics of EDA (exploratory data analysis), prediction algorithms (e.g. Least Squares, random forests), identification of sources of randomness in data, probabilistic models (e.g. linear regression), inference, and interpretation. We ground our class in the concepts of reality, representation of reality, and mental construct to separate current data, algorithms/models and future data in the context of domain knowledge. We discuss when and how to connect these three concepts in the entire process of data analysis. In particular, the PCS framework (workflow and documentation) based on the three principles of data science - predictability, stability and computability (PCS) will be employed as an overarching theme.

The lectures (and labs) will be based on real-data problems, and students will learn useful statistical concepts and methods in the contexts of these problems. The aim is to illustrate how judgement and common-sense are crucial to the statistical investigation process. Moreover, we introduce the technical topics through a first-principles approach so that students gain the skills necessary to develop new techniques to solve problems in unfamiliar situations in the future.

The essential elements of applied statistics are captured in Bin's piece entitled "Data Wisdom" ([http://www.odbms.org/2015/04/data-wisdom-for-data-science/](http://www.odbms.org/2015/04/data-wisdom-for-data-science/)). Students are asked to read the piece after the first lecture.

---

**Data lab format and peer-grading**
The data labs will be done individually, except for one group lab later in the semester. The goal of writing the lab report is not only to gain data analysis experience but is also an exercise in communication. We ask that particular attention is given to the writing of the report, as your peers will be reading them: so that the students can learn from one another, the labs will be peer-reviewed. Each student will review 2-3 labs from their peers, and will provide feedback and a grade based on several criteria including clarity of writing, validity of analysis and informativeness of visualizations. The final grade of each lab will be decided by the GSI who will use the student grades as a guide.

---

**Full commitment to the class is necessary** Please be aware that this class is a heavy workload. If you are not sure that you can commit, please audit the class instead since there are many students on the waitlist. Further, because class discussions are an integral part of the course, registered students are required to attend all classes unless permitted by the instructor under justifiable circumstances.

---

**Pre-requisites** In this class, we require knowledge of upper division mathematical statistics and probability courses (Stat 134 and 135) at UC Berkeley. In terms of computing, at a minimum you should be comfortable manipulating files in Unix and writing your own functions, manipulating and cleaning data and creating and customizing graphics in Python. Ideally, students will already have a basic fluency in Python as well as confidence using Github. While we will be providing a short introduction to these topics in the labs, students who are entirely unfamiliar with these tools will need to put in additional work to ensure that they meet the standards expected of the course.

---

**AI use policy**
* Lab report writing: use genAI only to polish at paragraph level after human writing.
* Code help: we have specific instructions for each lab.

## Tentative List of Topics

* Getting to know each other. Overview of the course. PCS (workflow and documentation) as the guiding framework for the course, where PCS stands for predictability, computability and stability (Aug. 27)
    * Aug. 28 First Discussion (Lab 0 assigned)
* Video guest lecture and zoom Q&A by Aaron Kornblith (UCSF) on data collection case study 1 (pediatric ER); The ER PECARN data problem will be investigated throughout the semester in the labs (Sept 1); PCS framework addresses issues of scientific reproducibility in data science and AI. PCS reality-check and stability consideration through appropriate data and algorithm perturbations. (Sept 3)
    * Sept. 5: Lab 0 due (midnight); Lab 1 assigned (on ER PECARN data cleaning)
* Domain question to answer (often about the future). Relevant data collection and cleaning, EDA (Sept. 8, 10)
* Unsupervised learning (PCA, NMF, and auto-encoder) and prediction problems: reality-check and stability consideration through appropriate data and algorithm perturbations. (Sept. 15, 17)
    * Sept. 19: Lab 1 due (midnight); Lab 1 peer review assigned; Lab 2 assigned (on clustering linguistic data)
* Least Squares (LS). 3-way data split: test set as best proxy for future data. Cross validation. Regularized LS: model selection, forward selection, L2boosting, (Sept. 22, 24 (video lecture by Stark on data collection regarding election auditing))
    * Sept. 25: Lab 1 peer review due (midnight)
* Lasso and Ridge. (Sept 29, Oct. 1)
    * Oct. 2: Lab 2 due (midnight); Lab 2 peer review assigned; Lab 3 assigned (computing and evaluating the stability of k-means)
* Weighted LS. Binary classification through WLS and logistic algorithms. Prediction with uncertainty measures. Calibration and evaluation or scrutiny of results. Sources of randomness. Simple random sampling. Density estimation and generative DL (Oct. 6, 8)
    * Oct. 10: Lab 2 peer review due (midnight)
* EM, Neyman-Rubin model for A/B testing, and linear regression models (Oct. 13, 15)
    * Oct. 17: Lab 3 due (midnight); Lab 3 peer review assigned
* Logistic Regression Model; Exponential Family. GLMs, (Oct. 20, 22)
    * Oct. 23: Lab 3 peer review due (midnight); Lab 4 assigned (group project)
* IRWLS, model checking through calibration. Supervised DL. (Oct. 27, Oct. 29)
* Nov 3: Midterm Review
* **Midterm Week**: In Class Midterm Nov. 5 (Bin will be on travel)
* Drawing conclusions from linear regression and logistic regression models through data and algorithm perturbations (or PCS inference). Interpretation of data results. Hypothesis testing, sequential testing, and multiple hypothesis testing. (Nov. 10, 12).
* Nov. 13: Lab 4 Due (midnight); Lab 4 peer review assigned; **Final project assigned**
* Tree-based methods (RF, RF+), AIC/BIC, e-L2boosting; Lasso theory; Kernel methods; Interpretable ML/DL. (Nov. 17, 19)
    * Nov. 20: Lab 4 peer review due (midnight)
* Some DL theory (Nov. 24, Nov 26 (Thanksgiving))
* PCS revisited and PCS-guided hypothesis generation (Dec. 1, 2 (guest lecture))
    * Dec. 5 Friday: Last lab session
* No in-class final exam, but there is a final project.

**Final Project Due**: Dec. 11 (midnight).

---

**Accommodations for Students with Disabilities**
Please see the instructor as soon as possible if you need particular accommodations, and we will work out the necessary arrangements. For more information on scheduling conflicts please refer to: [https://teaching.berkeley.edu/statements-course-policies#scheduling](https://teaching.berkeley.edu/statements-course-policies#scheduling)

---

**Academic Integrity**
One of the most important values of an academic community is the balance between the free flow of ideas and the respect for the intellectual property of others. We expect to uphold the university standards of academic integrity and UC Berkeley's honor code. Please read [https://teaching.berkeley.edu/statements-course-policies#academic](https://teaching.berkeley.edu/statements-course-policies#academic) for more information.

---

**Academic Freedom**
Students and instructors have the right to express their ideas and points of view in a respectful manner, even if those views differ from others. Strive to engage in open discussion and critical inquiry, while always respecting the diverse perspectives of others.

---

**Copyright Consideration**
Certain materials in this course, including lectures, notes, handouts, assignments, and online content, may be protected by copyright. Please seek written permission for distribution or reproduction of any material. Unauthorized sharing or distribution of course materials may constitute a violation of copyright law and university policy.

---

**Course Evaluations**
Students will be requested for a combination of written and verbal feedback on the course throughout the semester. At the end of the semester, students will be asked to fill out end of course evaluations for the course. Student feedback will help us plan for the future and make improvements.

---

**Safety & Emergency Preparedness**
Please refer to the following information for emergency preparedness at Evans Hall: [https://dac.berkeley.edu/navigating-berkeley/buildings/evans-hall](https://dac.berkeley.edu/navigating-berkeley/buildings/evans-hall)

---

**Disclaimer**
Please note the syllabus is subject to change and could be updated in the semester.
