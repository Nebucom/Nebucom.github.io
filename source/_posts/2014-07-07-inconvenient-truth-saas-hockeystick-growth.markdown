---
layout: post
title: "The Inconvenient Truth about SaaS Hockey Stick Growth"
date: 2014-07-07 14:23:34 +0200
comments: true
categories: metrics
author: Nick Boucart
---
> Running a SaaS business is a numbers game. Small changes in key figures like Churn or Customer Acquisition Costs (CAC) can have a serious impact on your cash flow. And while we are at it, hockey stick growth requires deep pockets of cash. In this post, we'll run you through some simulations to illustrate how.

Often times, you'll read about how SaaS companies are able to grow fast and furious. Hockey stick growth anyone? What is less known, is that, in order to grow so aggressively, SaaS companies need to dig a deep hole first. Recovery, and the proverbial hockey stick, comes months, often times years later. Check out [The Pay Later Cash Flow model](/blog/2014/04/02/pay-later-cash-flow-model/) for more details. 
<!-- more -->

## A few metrics that matter
Let's illustrate this with a simple example. I'll make a lot of short cuts in my model, only focusing on key metrics like churn rate, number of new customers per month, and the cost of sales.
Assume a startup SaaS company mySaaS.io. MySaaS.io offers its product through a monthly subscription plan of 49 euro per user per month. The company has 2 people on board doing sales and marketing. They spend their time generating content for their content marketing strategy, overlooking paid ad-campaigns and following up on leads trying to close deals. Let's assume all of these activities cost mySaaS.io 10.000 euro/month. The company is still early stage, so they are not onboarding 1000's of users/day, it's more in the order of 30 new paying customers/month. Since not all customers will stay forever with mySaaS.io, churn is not at 0, it's more like 6% monthly churn. (note: 6% might seem pretty high, but for a starting company still trying to nail down product/market fit, this is actually be not that bad)

This is how the cash flow evolution for mySaaS.io would look like, taking no other costs (dev, operations, whatever) into account. These numbers are way too optimistic, but they'll do to illustrate my point.
![Simulation 1: 30 new customers/month at 49 euro/month, 10000 sales&marketing budget, 6% churn](/images/saas-simulation1.png)
A nice hockey stick shows up, but it takes at least 18 months for the mySaaS.io to have more money coming in that it is spending. At their lowest point, the company will have a negative cumulative cash flow of over 33k euro, meaning that, if mySaaS.io does not have at least 34k euro on the bank at the start of this growth curve, they'd be dead in the water before they start seeing the upside of things. As a reminder and disclaimer: I only take sales&marketing costs into account, I pretend that it costs nothing to serve those customers and I neglect the costs of development and support staff. So in reality, the hole mySaaS.io is digging, will be considerably deeper than 34k euro.

## Small improvements in Churn and CAC matter a lot
Now, the good news is, that small changes can have a large impact. Let's consider previous example. The customer acquisition cost (CAC) is around 333 euro (10k euro/month brings in 30 new customers), for a life time value (LTV) of 816 euro. (LTV = monthly revenue for one customer divided by the monthly churn rate.) So, by being a bit more effective in sales & marketing, the team manages to land 33 customers (10% increase), while they reduce churn to 5% instead of 6%. 
![Simulation 2: 33 new customers/month at 49 euro/month, 10000 sales&marketing budget, 5% churn](/images/saas-simulation2.png)
As you can see, at this rate, the hole they dig is still as deep, but recovery goes faster (cash flow positive after month 15, instead of month 18) with a much bigger uptake. The key KPI's CAC and LTV are also much more positive in this scenario with 303 euro to acquire a customer for a LTV of 980 euro.

## Try for yourselves
What about your case? I've put online a little simulator for you so you can play around with the parameters too and check out how well your SaaS is doing. Feel free to leave a comment on your findings. You can find the simulator over at http://www.nebucom.be/saas-financial-planner/.

## Conclusions
In SaaS, lowering the cost of acquisition and churn rates can make a big difference on your cash flow. You shouldn't neglect small improvements, as demonstrated in the second simulations, even small improvement can have significant impact. 

> If you want to know more about SaaS pricing and cash flows, check out our [upcoming bootcamp](/blog/2014/06/16/Pricing-your-saas-bootcamp/) on SaaS pricing.
