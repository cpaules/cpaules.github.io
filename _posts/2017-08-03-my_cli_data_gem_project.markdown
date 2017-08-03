---
layout: post
title:  "My CLI Data Gem Project"
date:   2017-08-03 00:57:00 +0000
---


I just completed my CLI Data Gem Project! Overall I had fun doing it, except for when I got stuck on the scraper method. 

Before I got started, I watched and followed along with the video walkthrough in order to set up my gem. While I watched the video, I also thought of ideas for what to do for my project. 

The idea for my project was a movies app that gave the user details about movies in theaters. It starts out by propting the user for their zip code, then scrapping IMDB's movie list for the movie's title, rating, and director. It then creates Movie object which are created using their specific rating and director objects. After the scraping and object creating is done, it then prints out a menu for the user to interact with. The user has the following options: 
1. See more details about a movie
2. See the movies sorted by rating
3. See the directors along with which movie they directed
4. See the numbered list of movies

Much of the coding wasn't too difficult, but the scraper took me far too long to complete. I think it was difficult because IMBD's html uses a lot of span tags which took me a while to figure out how to use, and then I was iterating over the wrong div tag which I didn't notice for a very long time. I think I underestimated how useful and fluid rspec tests made my workflow, since I did this project without using rspec tests. Oh well, I think my project came out fine. 

Overall, it was fun and I had a good experience! Onwards and upwards
