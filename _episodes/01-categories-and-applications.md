---
title: "Major categories of machine learning"
teaching: 5
exercises: 0
questions:
- "What are the major categories of machine learning?"
- "What are some example applications for each?"
objectives:
- "Understand the major categories of machine and what kind of problems they can each solve."
keypoints:
- "machine learning categories, supervised learning, unsupervised learning, regression, classification"
---

# Major Categories of Machine Learning and Example Applications

![alt text](https://www.mathworks.com/content/mathworks/www/en/discovery/machine-learning/jcr:content/mainParsys3/discoverysubsection_1965078453/mainParsys/image_2128876021_cop.adapt.full.high.svg/1551847794310.svg){:class="img-responsive"}

<i>Figure: Major categories of machine learning (image source: MathWorks). </i>

## 1. Supervised Learning

Supervised learning learns a prediction model from past **input data** and **observed outcomes**, such that the prediction can take new input data and estimate outcome.

- **Sub-categories of supervised learning**:

    - **Regression**: outcomes are *continuous* values

        - Example applications:

            - Predict housing price given house size, location, number of rooms and year

            - Predict streamflow in the next week given mean annual streamflow, streamflow in the past week, rainfall in the past week and day of year

    - **Classification**: outcomes are *categorical* values

        - Example applications:

            - Classify handwritten digits

            - Land classification

![alt text](https://www.wolfram.com/mathematica/new-in-10/enhanced-image-processing/HTMLImages.en/handwritten-digits-classification/smallthumb_10.gif){:class="img-responsive"}

<i>Figure: Handwritten digits classification (image source: Wolfram).</i>

![alt-text](../assets/img/houston_flood.png "Logo Title Text 1"){:class="img-responsive"}
![alt-text](../assets/img/houston_flood_fcn.png "Logo Title Text 1"){:class="img-responsive"}

<i>Figure: Hurricane Harvey Houston flood mapping (upper panel: raw image; lower panel: flooding pixels classified).</i>

## 2. Unsupervised Learning

Unsupervised learning groups, interprets and find patterns in input data *without outcome data*. For example, unsupervised learning can be applied to identify groups (or **clusters**) in the data.

![alt-text](../assets/img/supervised_unsuper.png "Logo Title Text 1"){:class="img-responsive"}

<i>Figure: Illustration of supervised classification vs. unsupervised clustering. </i>



