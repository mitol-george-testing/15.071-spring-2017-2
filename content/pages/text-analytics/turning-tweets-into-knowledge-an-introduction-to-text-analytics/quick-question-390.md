---
content_type: page
parent_title: '5.2 Turning Tweets into Knowledge: An Introduction to Text Analytics'
parent_uid: aea3bc9c-07f7-3648-65c4-6fec93dd8515
title: '5.2 Turning Tweets into Knowledge: An Introduction to Text Analytics'
uid: ef17614f-a013-2a73-a771-05ff3c4311af
---

*   [<Video 6: Bag of Words in R]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-6-bag-of-words-in-r)
*   [5.2.1Video 1: Twitter]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics)
*   [5.2.2Video 2: Text Analytics]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-2-text-analytics)
*   [5.2.3Quick Question]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/quick-question-362)
*   [5.2.4Video 3: Creating the Dataset]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-3-creating-the-dataset)
*   [5.2.5Quick Question]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/quick-question-367)
*   [5.2.6Video 4: Bag of Words]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-4-bag-of-words)
*   [5.2.7Quick Question]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/quick-question-373)
*   [5.2.8Video 5: Pre-Processing in R]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-5-pre-processing-in-r)
*   [5.2.9Quick Question]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/quick-question-383)
*   [5.2.10Video 6: Bag of Words in R]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-6-bag-of-words-in-r)
*   [5.2.11Quick Question]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/quick-question-390)
*   [5.2.12Video 7: Predicting Sentiment]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-7-predicting-sentiment)
*   [5.2.13Quick Question]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/quick-question-395)
*   [5.2.14Video 8: Conclusion]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-8-conclusion)
*   [\>Video 7: Predicting Sentiment]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-7-predicting-sentiment)

Quick Question
--------------

In the previous video, we showed a list of all words that appear at least 20 times in our tweets. Which of the following words appear at least 100 times? Select all that apply. (HINT: use the findFreqTerms function)

Exercise 1

&nbsp;app&nbsp;

&nbsp;buy&nbsp;

&nbsp;freak&nbsp;

&nbsp;ipad&nbsp;

&nbsp;iphon&nbsp;

&nbsp;itun&nbsp;

&nbsp;like&nbsp;

&nbsp;love&nbsp;

&nbsp;new&nbsp;

&nbsp;think&nbsp;

Explanation

To answer this question, you need to run the following command in R:

findFreqTerms(frequencies, lowfreq=100)

This outputs the words that appear at least 100 times in our tweets. They are "iphon", "itun", and "new".

CheckShow Answer

*   [BackVideo 6: Bag of Words in R]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-6-bag-of-words-in-r)
*   [ContinueVideo 7: Predicting Sentiment]({{< baseurl >}}/pages/text-analytics/turning-tweets-into-knowledge-an-introduction-to-text-analytics/video-7-predicting-sentiment)