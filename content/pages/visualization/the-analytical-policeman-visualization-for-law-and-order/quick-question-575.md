---
content_type: page
parent_title: '7.3 The Analytical Policeman: Visualization for Law and Order'
parent_uid: 716f78f6-1fe6-c5f4-7370-d7a3c4127827
title: '7.3 The Analytical Policeman: Visualization for Law and Order'
uid: 578178b9-992b-b5c4-e6a9-8dc2f7c1ad78
---

*   [<Video 6: A Heatmap on the United States]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-6-a-heatmap-on-the-united-states)
*   [7.3.1Video 1: Predictive Policing]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order)
*   [7.3.2Quick Question]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/quick-question-540)
*   [7.3.3Video 2: Visualizing Crime Over Time]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-2-visualizing-crime-over-time)
*   [7.3.4Quick Question]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/quick-question-545)
*   [7.3.5Video 3: A Line Plot]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-3-a-line-plot)
*   [7.3.6Quick Question]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/quick-question-550)
*   [7.3.7Video 4: A Heatmap]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-4-a-heatmap)
*   [7.3.8Quick Question]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/quick-question-559)
*   [7.3.9Video 5: A Geographical Hot Spot Map]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-5-a-geographical-hot-spot-map)
*   [7.3.10Quick Question]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/quick-question-567)
*   [7.3.11Video 6: A Heatmap on the United States]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-6-a-heatmap-on-the-united-states)
*   [7.3.12Quick Question]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/quick-question-575)
*   [7.3.13Video 7: The Analytics Edge]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-7-the-analytics-edge)
*   [\>Video 7: The Analytics Edge]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-7-the-analytics-edge)

Quick Question
--------------

Redo the map from Video 6, but this time fill each state with the variable GunOwnership. This shows the percentage of people in each state who own a gun.

Which of the following states has the highest gun ownership rate? To see the state labels, take a look at [the World Atlas map](https://www.worldatlas.com/webimage/countrys/namerica/us.htm).

Exercise 1

&nbsp;California&nbsp;

&nbsp;Montana&nbsp;

&nbsp;Texas&nbsp;

&nbsp;Louisiana&nbsp;

&nbsp;Missouri&nbsp;

Explanation

You can generate the gun ownership plot using the following command:

ggplot(murderMap, aes(x = long, y = lat, group=group, fill = GunOwnership)) + geom\_polygon(color="black") + scale\_fill\_gradient(low = "black", high = "red", guide="legend")

Of these five states, the one that is the most red is Montana.

CheckShow Answer

*   [BackVideo 6: A Heatmap on the United States]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-6-a-heatmap-on-the-united-states)
*   [ContinueVideo 7: The Analytics Edge]({{< baseurl >}}/pages/visualization/the-analytical-policeman-visualization-for-law-and-order/video-7-the-analytics-edge)