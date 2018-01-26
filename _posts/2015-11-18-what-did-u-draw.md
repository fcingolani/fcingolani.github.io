---
layout:     page
title:      What did Ü draw
summary:    Frames from the Where Are Ü Now video by Skrillex and Diplo with Justin Bieber.
categories:
  - websites
permalink: websites/what-did-u-draw
banner: /media/2015-11-18-what-did-u-draw/banner.png
images:
  - /media/2015-11-18-what-did-u-draw/1.png
  - /media/2015-11-18-what-did-u-draw/2.png
  - /media/2015-11-18-what-did-u-draw/3.png
tech:
  - CoffeeScript
  - Node
  - ffmpeg
  - Tumblr API
---

Well, I've never thought I would be uploading [2324 pictures of Justin Bieber to the internet](http://whatdidudraw.tumblr.com)...

> "Where Are Ü Now" is a song produced and performed by American music producers Skrillex and Diplo under their collaborative effort Jack Ü.
>
> From May 29–31, 2015, there was an event held at the Jack Ü headquarters for fans to customize the photo-shoots for the "Where Are Ü Now" music video with crayons and colored pastels.
>
> [Wikipedia](https://en.wikipedia.org/wiki/Where_Are_%C3%9C_Now)

I've been watching [its video](https://www.youtube.com/watch?v=nntGTK2Fhb0) with my daughter a lot and from time to time i paused it to watch a random picture. I've found some really funny and/or creative paintings, and I thought it would be cool to be able to see every picture separately.

I've used *ffmpeg* to extract all the frames and made a custom uploader with *Coffee Script* / *Node.js* to upload only the painted ones to a [Tumblr blog](http://whatdidudraw.tumblr.com) which uses a custom theme I've made.
