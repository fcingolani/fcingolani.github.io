---
layout:     page
lang:       en
title:      Know Hearthstone
summary:    A Twitter bot that tweets one Hearthstone card a day.
categories:
  - bots
  - projects
permalink: know-hearthstone
banner: /assets/knowhearthstone-banner.png
tech:
  - Ruby
  - SQLite
---

<style>
@media screen and (min-width: 64em) {
  #twitter-widget-container {
    float: right;
    padding: 0px 0px 20px 20px;
  }
}
</style>

<div id="twitter-widget-container">
  <a class="twitter-timeline" data-dnt="true" href="https://twitter.com/KnowHearthstone" data-widget-id="677228643727376384">Tweets por el @KnowHearthstone.</a>
  <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
</div>

I've played Hearthstone during some months of 2014, and grew fond of the *flavor text* featured in every card. I've created a Twitter bot Ruby that:

1. Periodically retrieves cards information from [hearthstonejson.com](https://hearthstonejson.com), and stores it in an SQLite database. This keeps the pool of cards updated to the last patch.
2. Tweets a random card from that pool (never tweeted before) everyday at 8PM EDT.
