---
layout: post
title:      "Marvel CLI"
date:       2020-04-25 21:44:08 +0000
permalink:  marvel_cli
---


I started this project feeling overwhelmed by APIs and CLIs. I discovered a Marvel API that looked easy enough for a first-timer. Building my model was easy, but I couldn't figure out how to get information from the API! What was I doing wrong?? I followed all of the instructions and videos! I couldn't find the answer, so I had to get some extra help from my cohort lead. 

![](https://media.giphy.com/media/JSv2Yg4qUkEDGvYYqY/giphy.gif)

The answer was a Hash Key! I had to create a Hash Key in order to use my API.... ::cricket, cricket:: Put on your nerd hat...I'll do my best to explain what we did. 

A Hash Key is another version of your API Key that adds extra security. In this case, we needed to use my private API Key to create the hash as well as input my public key, and generate a new time stamp every time we access the data from the API. 

![MD5 algorithm](https://imgur.com/pI0ROaQ)

![Secrets file](https://imgur.com/gUTSnxH)

We had to first create an MD5 digest algorithm using a secrects file containing my API Keys to create a Hash Key. You can read more about the MD5 [here](https://en.wikipedia.org/wiki/MD5). 

We then had to add it all to the API Manager file so we could use it in the program. 

![API Manager file](https://imgur.com/qIBe0od)

If you ever need to figure this sort of thing out....you're welcome. I'm still not sure I understand it all, but it works!! I went through a period of time where I got so frustrated I decided to create a whole new project. Yep...I actually have 1.5 projects. After having through these feelings, I decided I should stick to my Marvel project. I knew I'd be proud of what I had accomplished...and I am!

> If it doesn't challenge you, it won't change you.

![Iron Man dancing](https://media.giphy.com/media/SX6AoXlEp2ri2IM9Fr/giphy.gif/)



