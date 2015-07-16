---
layout:     post
title:      "How to create infinite email addresses"
subtitle:   "A simple trick to prevent spam & unwanted email lists"
category:	"hacks"
date:       2015-05-08 22:00:00
author:     "Jonathan Baillie Strong"
header-img: "img/hacks/keyboard.jpg"
---

*I've split this post into 2 halves - first where I explain the rational behind the idea, the second where I explain the process I used - so feel free to <a href="#process">skip to the second part</a> if you're only interested in the "how-to" rather than the "why"*

___

There are a number of occasions where people might want to use a different email address than their own, for instance when:

- Creating multiple twitter accounts
- Trying to avoid spam
- Downloading a product where the creator requires you to sign up for a mailing list
- Signing up to a freemium model service numerous times

The excellent <a href="http://www.labnol.org/internet/multiple-email-addresses-in-gmail/17426/" target="blank">Digital Inspiration blog</a> describes how you can deal with this giving 2 ways of creating multiple email addresses: 

* Inserting symbols or adding affixes to your email
* Creating email aliases

In the first instance this means that if your email is hithere@gmail.com then messages addressed to either hi.there@gmail.com and hithere+goodlooking@gmail.com will all go to your inbox. The Second instance means you can create 'nicknames' in your gmail settings to also have other addresses arrive in your inbox.

These solve part of the first problem described (creating multiple accounts) but it doesn't really address the other use cases - avoiding spam or circumventing a mailing list signup as this will all be directed your main email inbox.

This is where <a href="mailinator.com">mailinator.com</a> comes in - it provides you with throwaway email addresses. Simply by visiting the website and typing in the email will allow you to access your throwaway account. However, many mailing lists and services have blacklisted mailinator addresses & in some instances you may want the emails to be accessed privately rather than publicly- and this is where linking a custom domain to mailinator makes more sense.

<div id="process">
<h2>The Process</h2>
</div>
As you'll probably be using these throwaway email addresses countless times, I suggest finding a short domain (which takes less time to spell) via <a href="http://shortdomainsearch.com/" target="blank">shortdomainsearch.com</a> - an up-to-date list of short, available, single word domain names. Once you've found one that's short and easy to type, register it on <a href="http://www.namecheap.com/?aff=53407" target="blank">Namecheap</a> - you can usually find a <a href="https://www.namecheap.com/promos/coupons.aspx">voucher code here</a> that will knock off a bit on the price. Using the shortdomainsearch.com I found a four letter domain with a .eu extension - one of the shortest ones available with an annual fee of $10 per year.

Once you've created your domain you can link it up to Mailinator by changing the domain's MX record to point to mail.mailinator.com <a href="https://www.namecheap.com/support/knowledgebase/article.aspx/322/78/how-can-i-setup-mx-record-for-my-domain" target="blank">as described here</a>.
You then need to login to mailinator with your gmail account, head over to <a href="https://www.mailinator.com/settings.jsp" target="blank">settings</a> and enter your domain there as shown below.


<div align="center">
    <img src="{{ site.baseurl }}/img/hacks/mailinator-settings.png" alt="Mailinator settings">
</div>

Once you've done that, you're good to go - every email address with your custom domain will appear in your own private inbox on mailinator - simply check the account when logged in with your google account.

<div align="center">
    <img src="{{ site.baseurl }}/img/hacks/pressing-something.gif" alt="Happy geek">
</div>