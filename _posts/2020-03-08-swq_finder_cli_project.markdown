---
layout: post
title:      "SWQ_finder CLI PROJECT"
date:       2020-03-09 01:13:32 +0000
permalink:  swq_finder_cli_project
---


This was a tough one. Having to do this at a local environment instead of the IDE sandbox, was a little rough for me.
Took me two days to get used to using vs code but I think i will start coding assignments on here more often. It took me around 5 days to finish coding and the first 3 days was installing the local environment into my mac and getting familar with it. another issue i had was to figure out the url of the api I'm using. Since each page only displays 10 characters, i thought about doing a loop to have it going but since I'm not pulling everying character / information from the api but specific characters, I had to abandon what I had coded earlier and restart.

I wanted to do something with starwars since there is a star wars API out there. the SWQ_finder works as it displays a list of quotes on the cli menu and allows user to choose whichever one they wanted. The hardest part for me in this project was turning the hash results into objects. I did my cli.rb file first, planned out what quote i want for this project and the outcome of each quote. After that I know I'd have to get certain results from the api. With the rest client and json method i was able to pull specific information i wanted from the api. Another struggle I had was to figure out the website url. Since each page only displayed 10 characters, I'd have to figure out a way to work around it and i set the base url and had a different string for character id so I'd just have to put in which character it was in my call method in the cli.rb file. This was much faster and easier than the method I had used a few days ago although it did took me a while to get it right. With all that done it is the part where I had to turn the hash that I got into objects. I did a resp get url with rest client and json.parsed it along with the symbolize_names command. That helped a bit with my resp_has results and I created a new variable with the character class that I created. Now I can return the information in objects ayeeeeeeee.

I worked on this project with a classmate of mine at a wework but since he is scraping and i'm doing the api thing, we couldn't really help each other but explaining your code out loud to someone really helps with your thinking. 
