---
layout:     post
title:      "Beyond wordpress"
subtitle:   "A rundown and comparison of six different blogging platforms"
category:	"blogging"
date:       2015-04-14 22:00:00
author:     "Jonathan Baillie Strong"
header-img: "img/home-bg.jpg"
---

Well I've tried out a whole bunch of blogging platforms - Wordpress, Medium, Tumblr, Ghost and now Jekyll. They all have their own quirks and each one is more suited to different intents & audiences. Here's a quick rundown with the pros and cons I've found for each. I've split this post into Two types of blogging platforms - those that are self hosted, where you own all of the rights to your content, and externally hosted platforms where you don't.

#Self hosted platforms
<div align="center">
    <img src="{{ site.baseurl }}/img/blogging/wordpress-logo.jpg" alt="Wordpress logo">
</div>
<span class="caption text-muted">"The most popular blogging system in use on the Web"</span>
Examples: <a href="http://techcrunch.com/" target="blank">Tech Crunch</a> | <a href="http://www.spectacularstays.com" target="blank">Spectacular Stays</a>

Wordpress is an all encompassing blogging platform that dominates online publishing, with over 20% of the world's websites using it as a content managing system (CMS) - according to [a recent interview its founder Matt Mullenberg](http://fourhourworkweek.com/2015/02/09/matt-mullenweg/). It was originally designed primarily to allow bloggers to easily create their own platform without any knowledge of coding but due to it's popularity has grown into a multi-purpose CMS, with extensibility and plugins allowing anyone from podcasters, marketers to large companies using it as well.

###Userbase/audience
<p class="lead">Anyone and everyone. </p>Professional bloggers will probably want to stick to this one but potentially leverage other platforms by reposting elsewhere later - Medium for instance.

###Pros
- The most fully featured and extendable platform out there
- If properly managed, a highly secure platform for any entity
- No coding knowledge required for a simple setup

###Cons
- Wordpress has become somewhat of a bloated swiss army knife that can do a million things, when often you just want it to do one thing (i.e. blogging) really well
- can be time consuming to keep up-to-date, format and so on
- Poor website speed performance and security on the most affordable option for hosting (shared). 

###Recommendations
- Go for self hosted (.org) rather than .com if you want to customise your own site, whether this be your own advertising, products or using advanced plugins
- If you're using it for a company or brand that will scale and has security concerns, consider investing in managed hosting (Synthesis, WPEngine - or Digital Ocean for the tech savvy) rather than shared - this will be much more secure.
- If you're considering going down the development route, may be worth considering a widely used framework (e.g. Genesis) - this will save 	you the time of having to relearn each theme. Personally I find any theme that uses visual composer incredibly hard to manage when it comes to websites with a significant amount of content.
- If you'd like to use the same theme as someone else's, use [this chrome extension](https://chrome.google.com/webstore/detail/wpsniffer/kihhefcbenhkjgjhchanjfhhflaojldn) or view the source code and search for 'theme'

___

<div align="center">
    <img src="{{ site.baseurl }}/img/blogging/ghost.png" alt="Ghost logo">
</div>
<span class="caption text-muted">"designed to simplify the process of online publishing for individual bloggers as well as online publications"</span>
Examples: <a href="http://taklo.co" target="blank">Tak Lo</a> | <a href="http://introsbective.com/" target="blank">Rebecca Collins</a>

Ghost is essentially a much more stripped down version of wordpress which makes it easier to do one thing - blogging. Allows you to see the markdown side by side with what a preview of what it will look like afterwards, like so:

<div align="center">
    <img src="{{ site.baseurl }}/img/blogging/ghost-markdown.png" alt="Ghost markdown">
</div>

###Pros
- simple to use once it has been set up
- you own the platform

###Cons
- tricky to do the initial set up

###Userbase/audience
People who just want to blog and don't really care about all the other bells and whistles.

###Recommendations
You can avoid the pitfalls of shared hosting by using Heroku to host your blog, which was free although recent pricing changes mean that this has changed.

___

<div align="center">
    <img src="{{ site.baseurl }}/img/blogging/jekyll-logo.png" alt="Jekyll logo">
</div>

Example: <a href="http://rsms.me/" target="blank">Rasmus Andersson </a>

This is the main blogging platform I am using and is the sole platform that can be hosted on Github. It's probably the most geeky of all of them.

<div align="center">
    <img src="{{ site.baseurl }}/img/blogging/jekyll-code.png" alt="Jekyll logo">
</div>

###Pros
- Hardly any security concerns
- you can blog offline, schedule a script to run and sync whenever online
- Can be hosted for free on Github
- Fast to load

###Cons
- Difficult to set up and requires technical expertise
- Scarcity of ready made themes
- Most of the themes available are pretty functional rather than pretty

###Userbase
**Programmers!**

###Recommendations
If using Jekyll for blogging it may be worth using <a href="http://bywordapp.com/" target="blank"> bywordapp.com</a> (or a load of other alternatives) as a text editor which allows you to write drafts in markdown. I'm currently using a jekyll theme which incorporates bootstrap which means I can use elements of the development framework I'm most familiar with, including [typography](http://getbootstrap.com/css/#type-body-copy) such as <mark>highlights</mark>, <del>deleted text</del> and so on.

___

#External hosting platforms

<div align="center">
    <img src="{{ site.baseurl }}/img/blogging/medium-logo.png" alt="Medium logo">
</div>
Example: <a href="https://medium.com/top-100/" target="blank">Top posts on Medium</a>

Medium is a slick, minimal platform which has become incredibly popular over the recent years.

###Userbase/audience
All sorts, but many people within the tech & startup scene who were the early adopters.

###Pros
- Free
- Incredibly easy to get started. Just sign in and start writing
- Nearly impossible to make look ugly
- Allows you to edit offline 
- Easy social sharing on twitter & facebook
- Easily share drafts
- Shows you useful stats of how widely read your posts are - note that the Twitter metric is incorrect - 

###Cons
- Readers tend to stay on the platform rather than following any Call To Action
- Nearly no way to customise

###Recommendations
- Use publications or contact the owners of large ones ([here's an out of date list](http://foorious.com/etc/list-of-medium-collections/)) to be featured there to get more views
- Share drafts of your posts with others - when they comment and you share the post afterwards, their twitter handles will all be mentioned & they will naturally repost
- Medium can be used to repost your own content originally hosted elsewhere

____


<div align="center">
    <img src="{{ site.baseurl }}/img/blogging/tumblr-logo2.jpg" alt="Tumblr logo">
</div>
Examples: <a href="http://blakemasters.com/" target="blank">Notes on Peter Thiel's lectures</a> | <a href="http://lucasjgordon.com/" target="blank">Lucas Gordon's blog</a> | <a href="http://slackhq.com/" target="blank">Slack HQ</a>

Tumblr is a micro blogging platform where again like Medium, you don't get the SEO juice that a self hosted platform offers, but it does provide an incredibly simple blogging platform that allows you to quickly share small snippets - which can be in the form of photos, gifs, video or otherwise. It allows you to repost other content, so in essence a micro blogging version of twitter.

###Userbase/Audience
Wide but popular with hipsters, young subcultures and surprisingly widespread in Brazil - the majority of [offline meetups](https://www.tumblr.com/meetups) appear to take place there.

###Pros
- Free
- Easy to set up
- Allows you to customise the look & feel more than Medium

###Cons
- Content doesn't belong to you
- Seems to be lagging behind Medium these days in terms of new functionality

###Recommendations
Tumblr allows you to point your own domain or subdomain (blog.yourdomain.com) there as oppose to Medium (although Medium have plans to move in that direction too)

___

There are more I could have mentioned - svbtle for instance, ([Maptia](http://www.maptia.com)) (essentially Medium for non-profits & travel bloggers/photogprahers), ([blogger](http://www.blogger.com)), typepad (where [Seth Godin's blog](http://sethgodin.typepad.com/) is hosted) and countless others. 

At the end of the day, it comes down to your intended audience, your preferred workflow and what you're most comfortable working with - in my case I already had a homepage hosted on Github, wanted something I could eaily set up as a /blog subdirectory and liked the facility that Jekyll offered of offline blogging so that was the easy choice.