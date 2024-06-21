+++
title = 'FirstDevBlogChipotle'
date = 2024-06-19T12:27:02-04:00
draft = false
+++

## Chipotle Social Media Site

Did some preliminary research yesterday and found that something very similar to what I want to do has already been done. The site has a map as the default background with pins for locations of Chipotle's that you can click and see the rating and other information for.

I would like to do something similar to this, but instead of just ratings and a few comments, I want to have a live feed, similar to Instagram, where you can see pictures and ratings of food that was just prepared at the location!

This will allow people to get a really good feel for if their cravings are going to be satisfied with the portion, or if they should just wait for another day.

Today, I will be working on gathering the data for the locations of all the Chipotle's in the US. I found a website that sells this data, but the price is **$95!** Absolutely not, if you are curious [this](https://www.scrapehero.com/location-reports/Chipotle-USA/) is the site that I found selling the data. 

I hope to be able to build a web scraper today that will gather the location data from Chipotle's location [page](https://locations.chipotle.com/), and store it into a database.

## End of day update:

I was able to get a scraper working in about 3 hours

I started the big run of the program before heading to the gym

The program failed because there wasn't a phone number on one of the locations

I fixed this by throwing some try except statements in the location where we search for those elements

I ran it again and got my first full set of [data](https://github.com/Timmermj10/ChipotleRater/blob/main/WebscrapLocationData/chipotle_locations_v1.csv)

I then made some adjustments to the process to make it run slightly faster and added some more data fields to gather to make the [dataset](https://github.com/Timmermj10/ChipotleRater/blob/main/WebscrapLocationData/chipotle_locations_v2.csv) more complete

I now have a full dataset similar to [ScrapeHero](https://www.scrapehero.com/location-reports/Chipotle-USA/), I plan to post the dataset on Kaggle to support other people looking for the data without having to pay the steep $95 price tag

I hope to start moving this data to a database tomorrow as well as some API work tomorrow!

Loooonnngggg coding day today! But I learned a lot about Beautiful Soup and it's capabilities!
