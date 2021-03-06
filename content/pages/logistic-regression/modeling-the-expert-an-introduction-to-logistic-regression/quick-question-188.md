---
content_type: page
parent_title: '3.2 Modeling the Expert: An Introduction to Logistic Regression'
parent_uid: 3063320a-4175-6b8a-4fa9-892f61b52c0d
title: '3.2 Modeling the Expert: An Introduction to Logistic Regression'
uid: d565e093-b63d-b842-9332-eabcb8503b85
---

*   [<Video 5: Thresholding]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-5-thresholding)
*   [3.2.1Video 1: Replicating Expert Assessment]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression)
*   [3.2.2Video 2: Building the Dataset]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-2-building-the-dataset)
*   [3.2.3Quick Question]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/quick-question-144)
*   [3.2.4Video 3: Logistic Regression]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-3-logistic-regression)
*   [3.2.5Quick Question]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/quick-question-152)
*   [3.2.6Video 4: Logistic Regression in R]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-4-logistic-regression-in-r)
*   [3.2.7Quick Question]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/quick-question-167)
*   [3.2.8Video 5: Thresholding]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-5-thresholding)
*   [3.2.9Quick Question]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/quick-question-188)
*   [3.2.10Video 6: ROC Curves]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-6-roc-curves)
*   [3.2.11Quick Question]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/quick-question-200)
*   [3.2.12Video 7: Interpreting the Model]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-7-interpreting-the-model)
*   [3.2.13Quick Question]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/quick-question-208)
*   [3.2.14Video 8: The Analytics Edge]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-8-the-analytics-edge)
*   [\>Video 6: ROC Curves]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-6-roc-curves)

Quick Question
--------------

This question asks about the following two confusion matrices:

Confusion Matrix #1:

| &nbsp; | Predicted = 0 | Predicted = 1 |
| --- | --- | --- |
| Actual = 0 | 15 | 10 |
| Actual = 1 | 5 | 20 

Confusion Matrix #2:

| &nbsp; | Predicted = 0 | Predicted = 1 |
| --- | --- | --- |
| Actual = 0 | 20 | 5 |
| Actual = 1 | 10 | 15 

What is the sensitivity of Confusion Matrix #1?

Exercise 1

&nbsp;Numerical Response&nbsp;

Explanation

The sensitivity of a confusion matrix is the true positives, divided by the true positives plus the false negatives. In this case, it is 20/(20+5) = 0.8

What is the specificity of Confusion Matrix #1?

Exercise 2

&nbsp;Numerical Response&nbsp;

Explanation

The specificity of a confusion matrix is the true negatives, divided by the true negatives plus the false positives. In this case, it is 15/(15+10) = 0.6

CheckShow Answer

Quick Question
--------------

To go from Confusion Matrix #1 to Confusion Matrix #2, did we increase or decrease the threshold value?

Exercise 3

&nbsp;We increased the threshold value.&nbsp;

&nbsp;We decreased the threshold value.&nbsp;

Explanation

We predict the outcome 1 less often in Confusion Matrix #2. This means we must have increased the threshold.

CheckShow Answer

*   [BackVideo 5: Thresholding]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-5-thresholding)
*   [ContinueVideo 6: ROC Curves]({{< baseurl >}}/pages/logistic-regression/modeling-the-expert-an-introduction-to-logistic-regression/video-6-roc-curves)