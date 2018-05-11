---
layout: post
title: BioPlus Patient Notes Viewer - 2016
category: project
subtitle: Single screen web-based app gives BioPlus intake specialists quick access ...
img_small: "notes.jpg"
img_large: "notes.jpg"
date: 2016-12-01 00:00:00
tags: []
siteURL: ""
previous_url: /bioplus-patient-dashboard/
next_url: /
permalink: /bioplus-notes-viewer/
---
This single screen web-based app gives BioPlus intake specialists and pharmacists quick access to the electronic medical notes of individual patients while verifying new drug orders and/or refills. The viewer is accessed via a modal launched from within the company's custom patient management software.     

![Notes Viewer]({{ "/images/" | append: page.img_large | prepend: site.baseurl | prepend: site.url  }})

### Coolest app features
Users can search patient notes data in a variety of ways (e.g., date range, keyword, column sorting). Note details for each record are inside panels that can be expanded or collapsed all at once or individually.  A member on the team built the API that I used to access the data.

### Biggest accomplishments
Building it from scratch in 3 weeks with no design or functionality requirements and making it appear as an integral part of the parent software. Customizing a javascript date-range-picker to appear seamless with the UI and filtering JSON data for the chosen date range was also a lot of fun.   

### Technologies used
* HTML5/CSS2/3
* JQuery
* Bootstrap
* AngularJS
* RESTful API with JSON
