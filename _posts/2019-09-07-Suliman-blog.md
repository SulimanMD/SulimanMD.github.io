---
layout: post
title: Data Science Bootcamp, Metis - First Project 
---
### Introduction

<p align="justify">During the first week in the Bootcamp, we learned a lot of things in Python and Mr. Trevor and Tony from Metis taught us the data science libraries that we need to use them in the first project such as Pandas, Numpy, Matplotlib, and Seaborn.</p>

<p align="justify">The first project was about doing exploratory data analysis <b>EDA</b> on New York City <b>NYC</b> subways data that was provided by the <a href= "http://web.mta.info/developers/turnstile.html"> MTA website </a>. Our client Women Tech Women Yes <b>WTWY</b> is a non-governmental organization (NGO) that needs to send their team to the NYC subway station to invite people to their gala by collecting emails from people and send to them a free ticket to enter their gala at the beginning of the summer. They want from us as a data scientist to provide them the best station, days, and times that they can send their team and collect the maximum amount of emails and invite people to their gala.</p>

#### Look at the stations using *MTA website*
[NYC subway map](http://web.mta.info/maps/submap.html)


### Project Approach

We had two phases to approach our project:

#### Phase 1: 

<p align="justify">Firstly, we spend three to five hours to brainstorm, understand what the data represent, and understand the problem. Secondly, we made an assumption of the maximum people who can pass one turnstile which is once per second which means the maximum people who can pass per 4 hours is approximately 15000 people. Lastly, we draw our plan to extract and analyze the data.</p>


#### Phase 2:

<p align="justify">In this phase, we have followed our steps to analyze the data that we draw in the first phase. Firstly, we asked ourselves since the event is in the beginning of the summer which mean in June, we have determined the analysis period from the first week in May until the first week in June which makes it 5 weeks. Secondly, we have extracted the NYC subway data from the <a href= "http://web.mta.info/developers/turnstile.html"> MTA website </a>. Thirdly, we have started to clean the data by deleting the negative values of the count in the entre's turnstile and deleting the unused columns. Lastly, we started to plot the graphs that we need to derive our insight then, we provided the client with our recommendation which contains the best station, days, and times that they can send their team to invite people.</p>


### Analysis and Recommendations

<p align="justify">The below graphs show the average daily inflows and outflows of the five weeks period that we choose, the top stations in terms of volume, and the average per station inflows for each day of the week.</p>

![Image test]({{ site.url }}/images/avg_inflow_outflow.png)
![Image test]({{ site.url }}/images/Top_5.png)
![Image test]({{ site.url }}/images/Average_per_station.png)

<p align="justify">Firstly, we noticed from the first figure above that the best days of the week to send the team are Wednesday, Thursday, and Friday. Secondly, from the second figure above we can clearly see that the top three stations in terms of the volume are 34 ST-PENN STA, GRD CNTRL-42 ST, and 34 ST-HERALD SQ. Lastly, we can see the average daily volume for each day with respect to the time. We noticed that in Friday trend between 5 and 7 there is a garbage data.</p>


Our recommendation:

|                         |                  Stations                            |Days                               |
| ----------------------- |:----------------------------------------------------:| ---------------------------------:|
| Recommended Station     | 34 ST-PENN STA, GRD CNTRL-42 ST, and 34 ST-HERALD SQ |                                   |
| Recommended days        |                                                      |   Wednesday, Thursday, and Friday |



<style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
p {
font-size:"12";
}
</style>
