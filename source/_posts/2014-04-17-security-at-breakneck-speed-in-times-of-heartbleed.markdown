---
layout: post
title: "Security at breakneck speed in times of Heartbleed"
date: 2014-04-17 14:05:06 +0200
comments: true
categories: security
picture: https://farm3.staticflickr.com/2441/3859852351_d65f71267b_n.jpg
---
<a href="https://www.flickr.com/photos/walkn/3859852351" title="Lock by walknboston, on Flickr"><img src="https://farm3.staticflickr.com/2441/3859852351_d65f71267b_n.jpg" width="267" height="320" alt="Lock" style="float:left; margin: 0 20px 10px 0"></a>
Today, an increasing number of companies are abandoning traditional, on-premise software packages for SaaS. And why wouldn’t they? Hosting your company software elsewhere enables you to rationalize investments, adapt more smoothly in a quickly evolving IT landscape, and access applications wherever you need them. In addition, software developers receive valuable user data, enabling them to update their solutions to fit their customers’ needs. But with that increased flexibility come some major security challenges. 
<!--more -->

Despite an increasing awareness of security and privacy issues in online applications — hello there, NSA — there is a remarkable online scarcity of information and best practices for software developers looking to step up their security levels. There is (http://www.owasp.org), for example; an open source community dedicated to improving the security of software.  As far as I know, however, only a few developers keep this treasure of information close to their chest. Odd, considering the grave consequences security breaches can have, resulting in the leak of sensitive information ranging from financial data and contacts thru’ to designs and engineering models. And in every single case, the developer’s reputation will be severely damaged. 

## Striking the right balance

In many aspects, the evolution toward SaaS demands a whole new perspective on IT security, at least for the SaaS providers. First, in the traditional software development model, software updates were rather infrequent. This allowed time for thorough security audits with every new version. Today’s SaaS applications, however, have a far higher release frequency — up to ten updates per day. For developers and providers, the challenge consists in finding a balance between adapting quickly to outsmart the competition and meet your clients’ needs, and offering the best possible protection. On top of that, most SaaS applications are built on top of numerous (open source) building blocks offered by third parties. They too have their release schedules, security issues, etc. Just last week, the discovery of the Heartbleed OpenSSL bug forced virtually all SaaS builders to update their servers as quickly as possible.

## Shielding floods of data

Second, the amount of data floating around nowadays is simply staggering. Successful SaaS providers—think SalesForce, Google AdWords, and many, many others—have millions and millions of customers. Their data is often stored in the same database, increasing the risk of undesired data flows. On top of that, most applications today don’t stand alone, but are part of an ecosystem where several solutions make use of each other’s components. For example, consider a Twitter app combined with a social media monitoring tool and a data visualization app, or CRM software that links to your e-mail app. This interconnectivity, as well as the fact that cloud- and SaaS solutions are globally accessible, makes them particularly vulnerable to threats and attacks.

In the next episode, we’ll discover how big data does more than just increase our vulnerability. When put to good use, it can also provide a solution to the challenges mentioned above. In fact, many companies are already doing that today. Keep your eyes peeled!
