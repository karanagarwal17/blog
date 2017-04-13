---
layout: post
title: "Data Visualization"
categories: Development
tags: [Data Visualization]
image:
  feature: data-vis.jpeg
  teaser: data-vis.jpeg
  credit:
  creditlink:
---

As a developer, when most people hear about Data Visualizations, the first thing that comes to their mind is use a library and write some code to create bar charts, graphs, line charts,etc. But as I dived deeper into the topic I realized there is more to it than just writing code.

Data Visualization is an art. It is presentation of data in such a way that it enables people to make decisions based on the visual analysis. It allows people to grasp difficult concepts and identify new patterns. These are some of the key points which I keep in mind to create effective Data Visualizations.

#### 1. Dont use redundant coding

Redundant coding refers to representing a data attribute by more than one visual structure. If data is visualized as circles plotted on a graph, an example of redundant coding would be if the same data attribute is used to decide the y co-ordinate of the circle as well as its radius. This should be avoided.

#### 2. Use of Pre-attentive Attributes

Pre-attentive attributes refer to the visual property which is processed by our brain without our conscious action. It takes less than 500 milliseconds for the eye and brain to process them. Thus they can be used to make it easier for the user to understand what is visualized by the data. Commonly used attributes are -
+ Color
+ Form
+ Movement
+ Spacial Positioning

#### 3. Use colors wisely
Colors should be used to draw attention to key pieces of data. They should not be too bright. Pastels can also be used to avoid straining the eyes.

#### 4. Keep high data-to-ink ratio

Data to ink ratio is the ratio of ink used to depict data upon the total ink used. Keeping this high would ensure that most of the ink is used in depicting data and the extra non-data ink could be removed. This would allow user to focus on the data completely and thus would help people in understanding the visualization more easily.

Some of the best ways to achieve this are -
+ remove the background
+ remove the 3-D effects
+ remove the border and grid
+ dont use different colors if the data is not color coded.

#### 5. Keep a check on the Lie Factor

Lie factor is ratio between the size of effect shown in a graphic and the size of effect in the data. It should be kept as close to 1 as possible. This ensures that the user gets accurate insight from the data.

### Twitter Live Data Visualization app

Keeping these key points in mind I created Twitter Live Data Visualization web-app which uses Data Visualizations to create a world-map and uses the Twitter Streaming API to fetch tweets with their location. It then plots the tweets on the map according to their co-ordinates and the number of followers the user has. Corresponding to every data a circle is plotted on the map whose location depends on the co-ordinates of the tweet and the radius is a function of the number of followers.

![Twitter Live Data Visualization]({{site.github.url}}/images/twitter.jpeg)

The source code for the project can be found on [Github](https://github.com/karanagarwal17/live-worldmap-visualization).
The project is hosted [here](http://karanagarwal.me/live-worldmap-visualization).
