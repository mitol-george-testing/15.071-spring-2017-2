---
content_type: page
parent_title: '4.2 Judge, Jury, and Classifier: An Introduction to Trees '
parent_uid: 11f9b44d-c296-0689-414b-8c313764a18d
title: '4.2 Judge, Jury, and Classifier: An Introduction to Trees '
uid: 0be06c80-7e39-cc4e-2808-dc63ffaa5efa
---

*   [<Video 6: Cross-Validation]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-6-cross-validation)
*   [4.2.1Video 1: The Supreme Court]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees)
*   [4.2.2Quick Question]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-253)
*   [4.2.3Video 2: CART]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-2-cart)
*   [4.2.4Quick Question]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-258)
*   [4.2.5Video 3: Splitting and Predictions]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-3-splitting-and-predictions)
*   [4.2.6Quick Question]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-267)
*   [4.2.7Video 4: CART in R]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-4-cart-in-r)
*   [4.2.8Quick Question]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-281)
*   [4.2.9Video 5: Random Forests]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-5-random-forests)
*   [4.2.10Quick Question]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-297)
*   [4.2.11Video 6: Cross-Validation]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-6-cross-validation)
*   [4.2.12Quick Question]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/quick-question-306)
*   [4.2.13Video 7: The Model v. The Experts]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-7-the-model-v-the-experts)
*   [\>Video 7: The Model v. The Experts]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-7-the-model-v-the-experts)

Quick Question
--------------

Plot the tree that we created using cross-validation. How many splits does it have?

Exercise 1

&nbsp;Numerical Response&nbsp;

Explanation

If you follow the R commands from the previous video, you can plot the tree with prp(StevensTreeCV).

The tree with the best accuracy only has one split! When we were picking different minbucket parameters before, it seemed like this tree was probably not doing a good job of fitting the data. However, this tree with one split gives us the best out-of-sample accuracy. This reminds us that sometimes the simplest models are the best!

CheckShow Answer

*   [BackVideo 6: Cross-Validation]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-6-cross-validation)
*   [ContinueVideo 7: The Model v. The Experts]({{< baseurl >}}/pages/trees/judge-jury-and-classifier-an-introduction-to-trees/video-7-the-model-v-the-experts)