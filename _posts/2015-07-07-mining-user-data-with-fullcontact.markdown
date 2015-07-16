---
layout:     post
title:      "Mining User Data with Google Sheets"
subtitle:   "Harnessing the power of the Full Contact API"
category:	"data"
date:       2015-07-07 22:00:00
author:     "Jonathan Baillie Strong"
header-img: "img/fullcontact/users.png"
---

The Full Contact API is able to provide a weatlth of information if provided with a list of emails. This was well [documented by BuiltVisable](https://builtvisible.com/fullcontact-api-excel/). They describe how [an Excel template](https://www.fullcontact.com/developer/docs/libraries/#excel-person-enrichment) can be used to pull all the social profiles available for individuals.  

Unfortunately, for anyone on a Mac & Chromebook  - the spreadsheet is unusable due to the macros only being compatable with excel on a PC machine.

Luckily I came across another template built in google spreadsheets by another developer which provides the same functionality. There were just 2 small minor issues I found with this template - firstly, it exceeded the API limits by making more than 60 requests per minute. Secondly, the row clearing function appeared to be causing errors. I made the small amendments to rectify these issues - and you can [**download the template here**](http://bit.ly/fullcontactapi). 

Here's a preview of it in action:

<div align="center">
    <img src="{{ site.baseurl }}/img/fullcontact/fullcontactapi.gif" alt="Executing the spreadsheet script for full contact">
</div>

Other alternatives to Full Contact API are also discussed on [the Growth Hackers website](https://growthhackers.com/questions/ask-gh-now-that-stacklead-is-gone-what-other-tools-will-tell-you-who-is-on-your-email-list/).