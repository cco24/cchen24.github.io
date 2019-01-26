---
layout: project
type: project
image: images/smstwilio.png
title: Sending SMS via Twilio
permalink: projects/sending-sms-via-twilio
# All dates must be YYYY-MM-DD format!
date: 2019-01-22
labels:
  - Python
summary: A program for sending SMS messages using Twilio.
---

<img class="ui small right floated square image" src="../images/smstwilio.png">

Learning how to navigate through a new operating system and discovering one's favorite aspects about it can be an interesting and exciting experience. However, the lack of the cross-platform characteristic in the applications and services one used on a previous operating system might dim the thrill of that experience and upset routine. My life revolves around a laptop but not so much a phone, and so, I was appreciative for iMessages since it allowed me to send and receive text messages on my MacBook to and from my iPhone, a feature I missed a lot when I started using a Windows laptop while still owning said iPhone. I was, thus, ecstatic when I saw the title of Chapter 16, "Sending Email and Text Messages", from Al Sweigart's [*Automating the Boring Stuff with Python*](https://automatetheboringstuff.com/), which I had been exploring through, where it teaches how to send SMS messages with Twilio. 

After reading it though, I realized this wasn't going to be my ideal "replacement" method for texting via laptop, but I was still interested in seeing the process and result of creating this Python program while also learning what Twilio is and how to use it. Twilio is a service that provides APIs for video, messaging, and voice communication for web and mobile applications. Before writing any actual code, I had to sign up for an account on their website in order to use their service. With that account, I could then register for a single Twilio phone number to send SMS messages from. Using the aforementioned book as my guide, I then began writing my program, with the following being the general layout of the code: import the necessary Twilio module, create a Client with my account SID and authentication token, and call the necessary function associated with that Client to send an SMS message from my Twilio number to my personal number. A result of my program is shown in the above picture: "hi from me" is the actual message I wrote while "Sent from your Twilio trial account" is the header that accompanies every message sent on a trial account, which was what I signed up for.

What I learned from this experience wasn't how to get around not being able to send and receive text messages between an iPhone and Windows machine, but the existence of a service that can be used in other amazing ways. 















