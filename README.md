# How to fetch Data from a restful api?
Hi! Im  Whirl and im gonna teach you how to fetch data from a restful api 
# What is a API?
API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the weather on your phone, you're using an API.
# How to make your own api?
This is not the topic of this tutorial but still [you can view it here!](https://canary.discord.com/channels/784691824790208512/784711943831289876/843086500022714428 "The discord message link")

[make sure to join that server to view](https://discord.gg/QspCPNuKpy "The discord server link")
# How to fetch data 
1 - you need to be familiar with json (it is really easy )

2 - for this tutorial i'll use this api - https://brawlapi.com

3 - now go the brawlers page in endpoints category

4 - they have listed a endpoint there 

5 - when you click on that link you see some text 

6 -  Now We would fetch that data and represent it on your console

7 - write this code -

```
 const fetch = require('node-fetch')//npm i node-fetch
fetch('https://api.brawlapi.com/v1/brawlers/16000038')
    .then(res => res.json())
    .then(json => console.log(json));
  ```
This would print what was on that endpoint page!

Now if you look closely they mention a brawler name , id , is released and much more !

How to get this content?

i'll use this method -
console.log(json.name) - this would log the brawler name which in this case is surge 

There may be some api's which have a more complicated json for [which traditional javascript method of reading objects can be used!](https://replit.com/talk/learn/JavaScript-Crash-Course-1000-Lines/135512 "How to read objects")

# Thanx To -
Whirl