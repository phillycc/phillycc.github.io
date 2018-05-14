---
layout: post
title: BioPlus Sales Dashboard - 2017
category: project
subtitle: RxCommunicator companion for sales staff to track and text with doctors ...
img_small: "salesdash.jpg"
img_large: "salesdash.jpg"
date: 2017-05-19 00:00:00
tags: []
siteURL: "https://sales.rxcommunicator.com/"
previous_url: /
next_url: /bioplus-rxcommunicator/
permalink: /bioplus-sales-dashboard/
---
As a critical companion to the RxCommunicator mobile app for doctors, this responsive single page web app (SPA) gave BioPlus account reps an interface to read and respond to text messages from their doctor offices (MDOs). The front-end of the Sales Dashboard was entirely of my own making, from design and layout to coding, testing, and product support. I also worked closely with our RESTful web API developer in defining the required HTTP requests and responses.       

![Notes Viewer]({{ "/images/" | append: page.img_large | prepend: site.baseurl | prepend: site.url  }})

### Coolest app features
I created functionality for administrators to support both the RxCommunicator mobile app and the Sales Dashboard. This included a feature that gave support personnel a window into what the doctor or registered staff member saw on his or her phone when responding to specific technical or data issues. I also provided admins with "one-click" functionality to register and to deactivate user accounts.

### Biggest accomplishments
* Working with token-based authentication and maintaining state in an AngularJS SPA, including http interceptors for handling refresh tokens. 
* Going from vague idea to full-blown AngularJS/RESTful responsive app in under 4 weeks, just in time for its roll-out at the annual BioPlus sales conference.

### Technologies used
* Bootstrap/HTML/CSS
* Javascript/jQuery
* AngularJS
* RESTful API with JSON
* MuleSoft's Anypoint Platform
* Postman
* Visual Studio Team Services with git 
