---
layout: post
title: Data Science Bootcamp, Metis - First Project 
---
### Introduction

During the first week in the bootcamp, we leaned a lot of things in Pyhon and Mr. Trevor and Tony from Metis taught us the data science libraries that we need to use them in the first project such as Pandas, Numpy, Matplotlib, and Seaborn.


The first project was about doing exploratory data analysis (**EDA**) on New York City (**NYC**) subways data that was provieded by [MTA website](http://web.mta.info/maps/submap.html). Our client Women Tech Women Yes (**WTWY**) is an non-govermental organization (NGO) that needs to send their team to the NYC subway station to invit people to their gala by collecting emails from people and send to them a free tacket to enter their gala in the biggining of the summer. They want from us as a data scientist to provide them the best station, days, and times that they can send their team and collect the maximum amount of emails and invit peope to their gala.


### Project Approach

We had two phases to approch our project:

#### Phase 1: 

Firstly, we speand three to five hours to brainstorm, understand what the data represent, and understand the problem. Secondly, we made an assumption of the maximum people who can pass one turnstile which is one per second which means the maximum people who cas pass per 4 hours is approximetly 15000 people. Lastly, we draw our plan to extract and analyze the data.


#### Phase 2:

In this phase, we have followed our steps to analyze the data that we draw in the first phase. Firstly, we asked ourselfs since the event is in the bigining of the summer which mean in June, we have determined the analysis period from the first week in May untill the first week in June which makes it 5 weeks. Secondly, we have exracted the NYC subway data from [MTA website](http://web.mta.info/maps/submap.html). Thirdly, we have started to clean the data by deleting the negative values of the count in the entre's turnsile and deleting the unused columns. Lastly, we started to plot the graphs that we need to derive our insight then, we provided the client with our recommendation which contains the best station, days, and times that they can send their team to invit people.



### Analysis and Recommendations

The below graphs show the average daily inflows and outflows of the five weeks period that we choised, the top stations in term of volume, and the average per station inflows for each day of the week. 

![Image test]({{ site.url }}/images/avg_inflow_outflow.png)
![Image test]({{ site.url }}/images/Top_5.png)
![Image test]({{ site.url }}/images/Average_per_station.png)

Firstly, we noticed from the first figure above that the best days of the week to send the team are Wednesday, Thursday, and Friday. Secondly, from the second figure above we can clearly see that the top three stations in term of volume are 34 ST-PENN STA, GRD CNTRL-42 ST, and 34 ST-HERALD SQ. Lastly, we can see the average daily volume for each day with respect to the time. We noticed that in Friday trend between 5 and 7 there is a garbage data.


 
