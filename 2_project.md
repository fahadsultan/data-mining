---
layout: page
title: Term Project
description: >-
    Course policies and information.
nav_order: 2
has_children: true
---

# Term Project
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc} 

---

In this course, you are expected to plan, execute, and present the results of a term-long group project of your choosing. 

Your project code should be on **[Github](https://github.com)**. Each group will be responsible to turn in **3-5 page project proposals and progress reports** as of the dates above.  

Take the time to investigate multiple options during the proposal phase.  You should have gotten some preliminary results by then, enough to provide confidence you will be able to successfully complete the project. 

### Groups 
Working alone on the project is strongly discouraged. Group sizes should range from **two to three students**. It is possible for multiple groups working on the same data set. However, such groups must work independently and are not allowed to share code or results. Each dataset leaves enough room to pursue different directions so I expect to see variety among the submissions from each group.

---

To ensure consistent progress, there is a project deadline roughly every 2 weeks. This will allow you to apply the techniques you learn in class to your project in a timely manner. 

**The steps of your project are to mirror the general data analysis pipeline**


### Identify or Collect a Data set  **Due September 15**{: .label .label-red }

Identify or collect a _publicly available_ data set that you will use for your project. A list of possible datasets and project ideas are [provided here](../2.%20data/) but you are allowed to propose your own project and data set. Just be mindful of the scale of the data: it should be large enough to be appropriate for usage in Machine Learning, but not so large that it is unwieldy. 

### Pre-processing **Due October 1**{: .label .label-red }

Preprocess data to change raw feature vectors into a representation that is more suitable for the downstream analysis. This may include data cleaning, calculating derivative or second-order variables, feature extraction, and feature selection. 
 
### Preliminary Analysis  **Due October 15**{: .label .label-red }

Perform some exploratory analysis to help you get acquainted with the data. This may include data visualization and basic preliminary analysis. Identify interesting aspects of the data set that would be useful for downstream prediction: correlations, outliers, missing values, etc.

### Unsupervised Learning  **Due November 1**{: .label .label-red }

Your project must involve atleast one unsupervised learning model. This should inform your supervised learning model. This may include, but is not limited to, clustering, dimensionality reduction, and density estimation.

### Supervised Learning and Evaluation **Due November 15**{: .label .label-red }

Identify, implement and apply a model covered in the class to predict some aspect of the data. This must be a supervised learning model. This may include, model selection, and model evaluation. 
    
You must compare your results to a number of baselines, including random predictor, major class classifier and/or autocorrelation model. An example table is shown below: 

| Model      | Accuracy | Precision | Recall | F1-score |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| Random baseline | 0.5       | 0.52 | 0.55 | 0.53 |
| Majority class / Autocorrelation   | 0.75       | 0.5 | 1 | 0.66 |
| Model 1   | 0.77       | 0.72 | 0.74 | 0.73 |
| Model 2   | **0.85**       | **0.79** | **0.89** | **0.88** |

### Analyze the results **Due December 1**{: .label .label-red }

Discuss the results of your analysis. This must include stating the assumptions of the model, the limitations of the model, a thorough error analysis and future directions.

### Presentation **Last two weeks of class**{: .label .label-red }

Present your findings to the class. This will be a 10 minute presentation followed by 5 minutes of questions.

---

### Peer Grading
A substantial part of the grading of the projects will be done by peers: each student will be charged with grading three other projects on the same topic. _Peer review is how research papers are selected for publication in academia_, and I hope this will be revealing.  I am hoping that this review will provide insights to improve your own projects as well.

To preserve **anonymity in submissions**, it is important that the papers you submit online for grading **not contain your names** or ID numbers. Indeed, the peer grading form/rubric will include a question if the grader can figure out whose paper they have, and if so we will take off points.
