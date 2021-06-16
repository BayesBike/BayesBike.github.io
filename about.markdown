---
layout: page
title: About
permalink: /about/
---

What is Bayes Bike?
--------------------
An analysis of bicycle crash data to understand how to make biking safer, based on the NYC crash data and an enrichment of that data. 

Who are we?
------------
[Thomas Proctor](https://github.com/ThomasProctor) and 
[Matthew Zadrozny](https://github.com/zadrozny).
Email us at Thomas.Chapman.Proctor [at] gmail [dot] com and m.zadrozny [at] gmail [dot] com.
 
Why “Bayes Bike”?
-------------------
[Thomas Bayes](https://en.wikipedia.org/wiki/Thomas_Bayes) was a statistician who devised a [theorem](https://en.wikipedia.org/wiki/Bayes%27_theorem) describing “the probability of an event, based on prior knowledge of conditions that might be related to the event. ” In our case, we are attempting to predict crashes ("pre-crash") based on any and all data we can obtain or infer, so that individual cyclists can bike defensively and city planners can more effectively intervene.  Also, Tom likes Bayes because, you know, alliteration. We reserve the right to use, or not use, any Baysian statistics.

Why are we doing this?
-----------------------
We're two data-driven New Yorkers on bikes trying to save lives and prevent injuries. Matthew has used up two of his nine lives on NYC streets. Tom lost his brother [Charlie to a bike crash](https://boston.cbslocal.com/2020/05/06/arlington-bicyclist-killed-crash-charles-proctor/), and hopes for a future where no one has to go through such pain and suffering.

Who is this for?
-----------------
We’re crunching the data to extract actionable insights for individual cyclists and patterns for the DOT and bike advocates.

What's in the NYC crash dataset?
-----------------------------------
As per the [NYC Open Data website](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95): "The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC" from 2012 to the present. Data is collected by police for "collisions where someone is injured or killed, or where there is at least $1000 worth of damage." The fields include date & time, geolocation / address, details on injuries and deaths, contributing factors, and types of vehicles. As of summer 2021, the crash data contains some 1.79 million rows over 29 columns, where each row represents a crash.


Fields missing from the (available) data include such things as whether it was day or night, the weather, the road direction, the presence or absence of a bike lane, and whether a helmet was worn. We are enriching the data with sources such as [DoITT](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#roadbed)  and [Open Street Map](https://www.openstreetmap.org) in order to gain a more complete picture. In the words of Charles Babbage: "The errors which arise from the absence of facts are far more numerous and more durable than those which result from unsound reasoning respecting true data." 

What questions are we trying to answer?
-------------------------------------------
- What aspects of road and road conditions make cycling more or less safe?
- Is it safer to bike by day or night?
- Do bike lanes affect the likelihood & severity of a crash?
- Does road width affect the severity of a crash?
- Is it safer to bike on a one way or two way road?
- Is it safer to bike in summer or winter?
- What weather conditions make biking more or less safe?
- Is it safer to bike on the driver or passenger side of a one-way road without a bike lane?
- Has the rise of Uber & Lyft made cycling more or less safe?  
- Has biking in NYC become safer or more dangerous in the last decade?

Under what license is the data and code?
--------------------------------------------
Much of our data, including the crash data set itself is published under NYC Open Data. “[There are no restrictions on the use of Open Data](https://opendata.cityofnewyork.us/faq/).” Data we have enriched is available under the same terms. The site is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
