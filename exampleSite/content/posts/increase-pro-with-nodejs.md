+++
date = "2020-02-23"
title = "Increasing your productivity with Telegram and Node.js"
slug = "increse-productivity-with-nodejs"
description = ""
series = ["Popular Posts", "Related Posts","Old Posts"]
+++

![Increasing your productivity with Telegram and Node.js](https://miro.medium.com/max/700/1*5fJjRL-3CDoWNJPfgaHm_Q.jpeg)

Some time ago I searched for an easy way to establish a communication channel between a mobile device and a Node.js webserver. My goal was to exchange messages over this channel and receive information about the weather, public transportation and more.  

For example I send the message /train and receive a response with realtime details about train departure times of preconfigured routes. So the Node.js server receives the incoming message, processes it and sends a response back to the client.  

After doing some researches I finally came up with Telegram bots since they are very easy to setup and fit perfect to my needs. Besides sending text messages, you can also share data like images or audio recordings.  

---

#### First of all, what exactly is a Telegram bot? ([Source](https://core.telegram.org/bots))

> Bots are third-party applications that run inside Telegram. Users can interact with bots by sending them messages, commands and inline requests. You control your bots using HTTPS requests to our bot API.  

So you simply send a message from your phone via Telegram and your webserver receives it over Telegram’s API.  
Just to name some of the things you can use your own bot for. Whether just for you or for your friends as well:  
* Gathering weather information
* Fetching arrival / departure times of public transportation
* Receiving tweets, news, status updates
* Sending automated messages
* IoT
and so much more.  

---

One big benefit of Telegram bots is that you don’t need a public server which is accessible over an IP-address from outside the network. In my case I use a Raspberry Pi to run the Node application for example.  

Since the communication takes place over the Telegram API, there’s just an internet connection required.  

For interacting with it you can use a runtime environment like Node.js as I did in the example app below or any other programming languages.  

[Here](https://core.telegram.org/bots/api) you can find an introduction about how to interact with the API.

---

As I mentioned above I recently created an example app for a Telegram bot server based on Node.js. Feel free to use it for your own bot and customize it according to your wishes or contribute to it.  

Let me know what you use your bot for and share your experience!  

Thanks for reading!