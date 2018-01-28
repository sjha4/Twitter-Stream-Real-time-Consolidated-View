# Real-time-Consolidated-View

The objective of this project is to develop a SaaS Web
Application/API Framework which provides real-time analytics of
current events using __Twitter, Reddit and Meetup streaming data__.
This tool can be used to visually identify active social gatherings and
help organize targeted activities with high audience participation

## PaaS Endpoint
API endpoint : https://dicteam8-restapi.herokuapp.com/ 

Below are some of the calls supported right now!
* /hour
* /day 
* /realtime 
* /getMeetupsForKeywordMonth/:keyword

## SaaS Endpoint

We have created a custom dashboard using the above mentioned API which is live here - 

https://dic8realtime-dashboard.herokuapp.com 

## Components:
1. SaaS Web Application that displays current information
on events like meetups/trends/news/forecast in real-time.

2. Application offers insights (Batch Analytics) of the data
with respect to different time frames such as
hour/day/month.

3. Application offers slice-dice operation as per the
demographics specified by user.
