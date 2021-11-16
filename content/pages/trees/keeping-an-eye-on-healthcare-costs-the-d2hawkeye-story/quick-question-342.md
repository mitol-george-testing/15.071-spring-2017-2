---
content_type: page
parent_title: '4.3 Keeping an Eye on Healthcare Costs: The D2Hawkeye Story '
parent_uid: 52a221dd-c011-90a4-45b1-a393b15cb810
title: '4.3 Keeping an Eye on Healthcare Costs: The D2Hawkeye Story '
uid: 954c1e9d-aed9-ccd1-65dd-85e2287df612
---

*   [<Video 6: Claims Data in R]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-6-claims-data-in-r)
*   [4.3.1Video 1: The Story of D2Hawkeye]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story)
*   [4.3.2Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-311)
*   [4.3.3Video 2: Claims Data]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-2-claims-data)
*   [4.3.4Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-316)
*   [4.3.5Video 3: The Variables]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-3-the-variables)
*   [4.3.6Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-321)
*   [4.3.7Video 4: Error Measures]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-4-error-measures)
*   [4.3.8Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-326)
*   [4.3.9Video 5: CART to Predict Cost]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-5-cart-to-predict-cost)
*   [4.3.10Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-337)
*   [4.3.11Video 6: Claims Data in R]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-6-claims-data-in-r)
*   [4.3.12Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-342)
*   [4.3.13Video 7: Baseline Method and Penalty Matrix]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-7-baseline-method-and-penalty-matrix)
*   [4.3.14Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-349)
*   [4.3.15Video 8: Predicting Healthcare Cost in R]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-8-predicting-healthcare-cost-in-r)
*   [4.3.16Quick Question]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/quick-question-357)
*   [4.3.17Video 9: Results]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-9-results)
*   [\>Video 7: Baseline Method and Penalty Matrix]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-7-baseline-method-and-penalty-matrix)

Quick Question
--------------

What is the average age of patients in the training set, ClaimsTrain?

Exercise 1

&nbsp;Numerical Response&nbsp;

What proportion of people in the training set (ClaimsTrain) had at least one diagnosis code for diabetes?

Exercise 2

&nbsp;Numerical Response&nbsp;

Explanation

Both of these answers can be found by looking at summary(ClaimsTrain). The mean age should be listed under the age variable, and since diabetes is a binary variable, the mean value of diabetes gives the proportion of people with at least one diagnosis code for diabetes.

Alternatively, you could use the mean, table, and nrow functions:

mean(ClaimsTrain$age)

table(ClaimsTrain$diabetes)/nrow(ClaimsTrain)

CheckShow Answer

*   [BackVideo 6: Claims Data in R]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-6-claims-data-in-r)
*   [ContinueVideo 7: Baseline Method and Penalty Matrix]({{< baseurl >}}/pages/trees/keeping-an-eye-on-healthcare-costs-the-d2hawkeye-story/video-7-baseline-method-and-penalty-matrix)