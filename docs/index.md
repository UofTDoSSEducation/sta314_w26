---
layout: home
title: "STA314: Statistical Methods for Machine Learning I"
---

## Overview

Machine learning (ML) is a set of techniques that allow computers to learn from data and past experience, rather than requiring humans to specify the desired behaviour by hand. ML has become increasingly central both in statistics as an academic discipline, and in the data science industry. This course provides a broad introduction to commonly used ML methods, as well as the key statistical concepts underlying ML. It serves as a foundation for more advanced courses, such as STA414 (Statistical Methods for Machine Learning II).

We will cover popular statistical methods for supervised and unsupervised learning from data as well as important concepts used in the field, including: training error, test error and cross-validation; classification, regression, and logistic regression; variable selection; penalized regression; principal components analysis; stochastic gradient descent; decision trees and random forests; neural nets; k-means clustering and nearest neighbour methods. Computational tutorials will support effective application of these methods.

---

<br />

## Annoucement

- The first lecture is on Jan 5th.
  
---
<br />

## Course information

### Course email and textbooks

- Course email: [sta314@course.utoronto.ca](mailto:sta314@course.utoronto.ca) (for requests and communication with the teaching group)
- Textbook: [An Introduction to Statistical Learning (ISL)](https://www.statlearning.com) 
- References:
  - Elements of Statistical Learning (ESL).
  - Pattern Recognition and Machine Learning (PRML).
  - Convex Optimization by Boyd and Vandenberghe (ConvOpt).
- Piazza: [sign-up link](https://piazza.com/utoronto.ca/winter2026/sta314).
- [Syllabus](/lectures/syllabus.pdf).

### Staff

| Instructor | email |  office |  office hours (OH) |  OH mode | 
| --- | --- | --- |  --- | --- |
| [Xin Bing](https://www.statistics.utoronto.ca/people/directories/all-faculty/xin-bing) |  [xin.bing@utoronto.ca](mailto:xin.bing@utoronto.ca) | UY 9192 | Wed (9-10am)  |  Zoom <!--[Zoom link](https://utoronto.zoom.us/j/81581102645) --> | 

### TAs

| Section | TA  | OH | OH mode |  
| --- | --- | --- | --- |  
| LEC0101 | Haochen Song | TBA | TBA <!-- [Zoom link](https://utoronto.zoom.us/j/82036868816) --> |  
|  | Xiaochuan Shi | TBA | TBA <!-- [Zoom link](https://utoronto.zoom.us/j/82036868816) --> |  
|  | Morris Greenberg  | TBA | TBA | 
|	 | Groﬀ William  |	TBA <!--Fri (9am-10am)--> | TBA |   

### Lectures 

| Section	| Time	| Location | 
| --- | --- | --- |
| LEC0101	| Mon (3-4pm)  | PB B150 | 
| 	| Wed (3-5pm)  | PB B250 | 

### Tutorials 

| Section | Session | Time | Location | TA | 
|--- | --- | --- | --- | --- |
| LEC0101 | 101 | Mon (4-5pm) | MC |   |
| | 102 |  |  MS  |   |
| | 103 + 104 |  |   MC  |  | 
 
---

<br />


## Grading scheme

|  | Date | Time & Location |  Credit | Content | Solution |
|---|---|---|---|---| --- |
| Quizzes | NA | During tutorials | 5% | | | 
| Midterm | Feb 11 | 3-5pm;  EM 119, PB B250, VC 206, VC 215 | 35% | Weeks 1-5 | <!--[[sol-101.pdf](/tests/midterm1-101-sol.pdf)] <br> [[sol-201.pdf](/tests/midterm1-201-sol.pdf)]-->  |
| Final  | TBA | TBA |   35% | Weeks 1-10 | |
| Project | Jan 19 |  Group sign-up: by Feb 2, 11:59pm, poll form <br /> Kaggle competition: start on Feb 2, 11:59pm, due on Mar 20, 11:59pm  <br /> Report due: Mar 22, 11:59pm, Quercus | 25% | <!-- [[Documentation](https://q.utoronto.ca/courses/354759/files/33406865?wrap=1)]--> <!-- <br> [[Report outline](https://q.utoronto.ca/courses/354759/files/34537849?wrap=1)] --> | |

<!--| [Homework 3](/hws/hw3/hw3.pdf) | Nov 2, 12 AM | Nov 19, 11:59 PM | 10% | Lec06-08 | [[Q1-Q3.pdf](/hws/hw3/hw3_solution_Q1_Q3.pdf)],[[Q4-Q5.pdf](/hws/hw3/hw3_solution_Q4Q5.pdf)] |
| [Homework 4](/hws/hw4/hw4.pdf) | Nov 16, 12 AM | Nov 29, 11:59 PM  | 10% | Lec06-10 | [[sol-derivation](/hws/hw4/hw4_solution_derivation.pdf)], [[sol-coding](/hws/hw4/hw4_solution_coding.pdf)]  |-->

---

<br />

## Practical problem sets

| | File | Solution | Content |
|---|---|---|---| 
|Problem set 1|  [[Problem set 1](/practical_sets/set1.pdf)]  |  [[Sol:Q1-Q4](/practical_sets/set1_sol_Q1-Q4.pdf)], [[Sol:Q5](/practical_sets/set1_sol_Q5.pdf)]  | Weeks 1-2 |
|Problem set 2| <!-- [[Problem set 2](/practical_sets/set2.pdf)] --> | <!-- [[Sol:Q1](/practical_sets/set2_sol_Q1.pdf)], [[Sol:Q2-Q4](/practical_sets/set2_sol_Q2-Q4.pdf)]-->  | Weeks 2-4 |
|Problem set 3|  <!--  [[Problem set 3](/practical_sets/set3.pdf)] --> | <!--  [[Sol:Q1-Q3](/practical_sets/set3_sol_Q1-Q3.pdf)], [[Sol:Q4Q5](/practical_sets/set3_sol_Q4Q5.pdf)] --> |  Weeks 4-6 |
|Problem set 4| <!--  [[Problem set 4](/practical_sets/set4.pdf)], [[Q2_starter.zip](/practical_sets/set4_Q2_starter.zip)],  [[Q3_starter.zip](/practical_sets/set4_Q3_starter.zip)] --> | <!-- [[Sol-derivation](/practical_sets/set4_sol_derivation.pdf)], [[Sol-coding](/practical_sets/set4_sol_coding.pdf)] --> | Weeks 5-7 | 
|Past midterms| <!--  [[Midterm 23Fall](/practical_sets/midterm23fall.pdf)] --> |   |
|Past finals| <!-- [[Final 23Fall](/practical_sets/final23fall.pdf)] --> | <!-- [[Final 23Fall_sol](/practical_sets/final23fall-sol.pdf)] --> |  | 

---

<br />


## Lectures 

This is a preliminary schedule; it may change throughout the term. 

| Week | Dates	| Lecture Topic	| Lecture Slides	| Suggested Readings |
| --- | --- | --- | --- | --- | 
| 1 | Mon, Jan 5 | Course logistics <br /> Intro to Machine Learning    |  [[Lec-logis.pdf](/lectures/lec-logistics.pdf)]   | ISL 1   |
| | Wed, Jan 7 |  Intro to Statistical Learning  <br /> The bias-variance tradeoff  |  [[Lec-BVT.pdf](/lectures/lec-BVT.pdf)]  |  [[Linear algebra & Probability](/tutorials/review_alg_prob.pdf)] <br/> ISL 2.1-2.3    |
| 2 | Mon, Jan 12 |   Linear regression  | [[Lec-LR.pdf](/lectures/lec-LR.pdf)] |  ISL  3.1-3.3, 3.6    |
| |  | Tutorial 1 (linear regression) | <!--  [[Notes](/tutorials/tut01.pdf)], [[R code](/tutorials/tut01_coding.Rmd)], [[Python code](/tutorials/tut01_coding.ipynb)] -->  | ISL 3.6 |
| | Wed, Jan 14 |  Cross-validation  <br/> Model selection under LMs | [[Lec-CV.pdf](/lectures/lec-cv.pdf)]  | ISL 5.1, 6.1, 6.2, 6.4 <br /> ESL 7.10  |
| 3 | Mon, Jan 19 |  Shringkage regression | [[Lec-SR.pdf](/lectures/lec-SR.pdf)]  | ISL 6.1-6.4 <br /> ESL 7.10  |
| | | Tutorial 2 (Subset selection) | <!--  [[Notes](/tutorials/tut02.pdf)], [[R code](/tutorials/tut02_coding.Rmd)], [[Python code](/tutorials/tut02_coding.ipynb)] --> | ISL 5.3.1-5.3.3, 6.5.1 |
| | Wed, Jan 21 | Shringkage regression <br/> Gradient descent  | [[Lec-SR.pdf](/lectures/lec-SR.pdf)] <br/> [[Lec-GD.pdf](/lectures/lec-GD.pdf)]  | ISL 4.3, 4.4 <br /> ESL 4.3, 4.4 <br/> PRML 4.1, 4.3 <br />  ConvOpt 2.1-2.3, 3.1-3.2, 4.1-4.2 <!--[[Multivariate calculus](/tutorials/review_multi_calculus.pdf)]--> | 
| 4 | Mon, Jan 26 | Gradient descent <br/> Move beyond linearity | [[Lec-GD.pdf](/lectures/lec-GD.pdf)]  <br/>  [[Lec-NLR.pdf](/lectures/lec-NLR.pdf)]  | ISL 7.1-7.4, 7.6, 7.7  |
| | | Tutorial 3 (Shrinkage and GD) |  <!--  [[Notes](/tutorials/tut03.pdf)],  [[R code](/tutorials/tut03_coding.Rmd)], [[Python code](/tutorials/tut03_coding.ipynb)] --> | ISL 6.5.2 | 
| | Wed, Jan 28 | Move beyond linearity |   [[Lec-NLR.pdf](/lectures/lec-NLR.pdf)]  | ISL 7.1-7.4, 7.6, 7.7  |
| 5 | Mon, Feb 2 |  Introduction to classification |  [[Lec-classification.pdf](/lectures/lec-classification.pdf)]   | ISL 4.1, 4.2  |
| | | Tutorial 4 (Beyond linearity) | <!--  [[R code](/tutorials/tut04_coding.Rmd)], [[Python code](/tutorials/tut04_coding.ipynb)] --> | ISL 7.8 |
| | Wed, Feb 4  |  Logistic regression   | <!-- [[Lec07.pdf](/lectures/lec-LR-binary.pdf)] --> | ISL 4.3, 4.4 <br /> ESL 4.3, 4.4 |  
|  6 | Mon, Feb 9  | Multi-class logistic regression  | <!--  [[Lec09-LR.pdf](/lectures/lec-LR-multi.pdf)] --> |  ISL 4.3-4.4 <br /> ESL 4.3-4.4 | 
| | | Tutorial 5 (MLE and LR) | <!--  [[Notes](/tutorials/tut06_note.pdf)]  --> | |
| | Wed, Feb 11 |  **Midterm** | | |
| 7 | Mon, Feb 23 |  Discriminant analysis   | <!--  [[Lec09-DA.pdf](/lectures/lec-DA.pdf)] --> | ISL 4.3-4.4   |
| | Wed, Feb 25 |   Discriminant analysis <br/> Support vector machine |   <!--   [[Lec10-SVM.pdf](/lectures/lec-svm.pdf)] --> |      ESL 4.3-4.4 |
| 8 | Mon, Mar 2  |  Support vector machine  | <!--  [[Lec10-SVM.pdf](/lectures/lec-svm.pdf)] --> | ESL 4.3-4.4   |
|  |  |  Tutorial 6 (DA and SVM) | <!-- [[Notes](/tutorials/tut07.pdf)], [[R code](/tutorials/tut-DA.Rmd)]--> | ISL 8.3, 9.6 |  
| | Wed, Mar 4 |  k-nearest neighbour <br/> Decision tree    | <!-- [[Lec11-DT.pdf](/lectures/lec-DT.pdf)] --> |   ISL 8.1 <br > ESL 9.2 |
| 9 | Mon, Mar 9 |  Decision tree, Bootstrap  |  <!--  [[Lec12-ET.pdf](/lectures/lec-ET.pdf)] --> |  ISL 5.2, 5.3.4, 8.2 <br /> ESL 7.11, 8.7, 10.1, 15 <br /> [[Gradient boosting machine](/tutorials/gradient_boosting_machine.pdf)], <br> [[R code on tree-based algorithms](/tutorials/tut-DT-ET.Rmd)] | 
| | Wed, Mar 11 |  Bagging, Random forest, Boosting |  <!-- [[Lec12-ET.pdf](/lectures/lec-ET.pdf)]--> |  ISL 5.2, 5.3.4, 8.2 <br /> ESL 7.11, 8.7, 10.1, 15 <br /> [[Gradient boosting machine](/tutorials/gradient_boosting_machine.pdf)], <br> [[R code on tree-based algorithms](/tutorials/tut-DT-ET.Rmd)] | 
| 10 | Mon, Mar 16 |  Neural network | <!--[[Lec13.pdf](/lectures/lec13.pdf)]--> | ISL 10, ESL 11 |   
| | | Tutorial 7 (Tree-based algorithms) | | |
| | Wed, Mar 18 | Neural network |  | ISL 10, ESL 11 | 
| 11 | Mon, Mar 23 |  Neural network |   | ISL 10, ESL 11 | 
| | | Tutorial 8 (Neural nets) | | |
| | Wed, Mar 25 |  Clustering  | <!--[[Lec-km.pdf](/lectures/lec-km.pdf)]--> | ISL 12.1 - 12.3 <br /> ESL 14.3 <br /> PRML 9.1 | 
| 12 | Mon, Mar 30  |  PCA | <!-- [[Lec-pca.pdf](/lectures/lec-pca.pdf)]--> | ISL 12.1 - 12.3 <br /> ESL 14.3 <br /> PRML 9.1 |  
| | Wed, Apr 1 | Proj presentation | | | 

<!-- 
| | Wed, Nov 27 | Unsupervised learning <br /> K-means clustering and PCA | [[Lec15.pdf](/lectures/lec15.pdf)] | ISL 12.1 - 12.3 <br /> ESL 14.3 <br /> PRML 9.1 | 
| | Wed, Nov 27 | Neural network |[[Lec13.pdf](/lectures/lec13.pdf)] | ISL 10, ESL 11 | 
-->
