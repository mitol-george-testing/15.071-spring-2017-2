---
content_type: page
parent_title: '2.2 The Statistical Sommelier: An Introduction to Linear Regression'
parent_uid: 4495fb48-3934-3c33-23b2-2ef2104af559
title: '2.2 The Statistical Sommelier: An Introduction to Linear Regression'
uid: dba3745d-05fd-fdd2-c5cc-f0b06194ed26
---

*   [<Video 4: Linear Regression in R]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-4-linear-regression-in-r)
*   [2.2.1Video 1: Predicting the Quality of Wine]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression)
*   [2.2.2Quick Question]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/quick-question-46)
*   [2.2.3Video 2: One-Variable Linear Regression]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-2-one-variable-linear-regression)
*   [2.2.4Quick Question]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/quick-question-54)
*   [2.2.5Video 3: Multiple Linear Regression]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-3-multiple-linear-regression)
*   [2.2.6Quick Question]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/quick-question-73)
*   [2.2.7Video 4: Linear Regression in R]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-4-linear-regression-in-r)
*   [2.2.8Quick Question]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/quick-question-78)
*   [2.2.9Video 5: Understanding the Model]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-5-understanding-the-model)
*   [2.2.10Quick Question]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/quick-question-88)
*   [2.2.11Video 6: Correlation and Multicollinearity]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-6-correlation-and-multicollinearity)
*   [2.2.12Quick Question]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/quick-question-96)
*   [2.2.13Video 7: Making Predictions]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-7-making-predictions)
*   [2.2.14Quick Question]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/quick-question-101)
*   [2.2.15Video 8: Comparing the Model to the Experts]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-8-comparing-the-model-to-the-experts)
*   [\>Video 5: Understanding the Model]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-5-understanding-the-model)

Quick Question
--------------

In R, use the dataset [wine (CSV)]({{< baseurl >}}/resources/wine-1) to create a linear regression model to predict Price using HarvestRain and WinterRain as independent variables. Using the summary output of this model, answer the following questions:

What is the "Multiple R-squared" value of your model?

Exercise 1

&nbsp;Numerical Response&nbsp;

What is the coefficient for HarvestRain?

Exercise 2

&nbsp;Numerical Response&nbsp;

What is the intercept coefficient?

Exercise 3

&nbsp;Numerical Response&nbsp;

Explanation

In R, create the model by typing the following line into your R console:

modelQQ4 = lm(Price ~ HarvestRain + WinterRain, data=wine)

Then, look at the output of summary(modelQQ4). The Multiple R-squared is listed at the bottom of the output, and the coefficients can be found in the coefficients table.

CheckShow Answer

*   [BackVideo 4: Linear Regression in R]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-4-linear-regression-in-r)
*   [ContinueVideo 5: Understanding the Model]({{< baseurl >}}/pages/linear-regression/the-statistical-sommelier-an-introduction-to-linear-regression/video-5-understanding-the-model)