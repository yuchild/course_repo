Business Analytics for Data Scientists
======================================

A data scientist must understand their company’s business model in order to be successful. Companies make substantial investments in data science, and the return on those investments hinges on how well their data scientists’ work serves that business model. As a result, the ability to derive the most strategically important insights and models from a business goal determines which data scientists get hired and, especially, which get promoted. Honing that ability is the purpose of this document and subsequent case studies.

Each of the following sections explains a common business model, a conceptual framework for analyzing each business model, and related metrics. Please answer these [review questions](https://docs.google.com/forms/d/1wrwJNr8DNeMDIS1kjqy3Lp7JC2hpio762f4Y5Po4WEs/edit?usp=sharing) as you read.

E-Commerce
----------

The basic e-commerce model is simply a website that sells products, such as Walmart.com, and the most important framework for understanding e-commerce is the funnel.

The funnel models how many customers proceed through each stage of the buying process. There can be many different funnels for a single business. For example, some visitors on the homepage may go to search results while others click on recommended products. This funnel depicts a homepage --> search --> purchase funnel.

![](../images/E-commerce_Funnel.png)  

Many of e-commerce’s key metrics describe how users behave in the funnel.

**Number of Visitors**  
size of the top layer of your funnel

**Bounce Rate**  
% of people who don't make it past first stage of the funnel  
e.g. % of homepage visitors who don't click on anything

**Click-through Rate (CTR)**  
![](../images/CTR.png)  
e.g.  
![](../images/CTR_example.png) 

**Conversion-Rate (CVR)**  
![](../images/CVR_1.png)  
OR  
![](../images/CVR_2.png)  
(The denominator of CVR can represent different things, depending on context.)

**Avg. Transaction Size**  
$ average size of transactions


In addition to funnel metrics, customer acquisition and retention metrics are important to an e-commerce company.

**Customer Acquisition Cost**  
How much a company must spend to get someone to buy for the first time.   
e.g.  
![](../images/Avg_CAC.png)  
![](../images/Avg_CAC_2.png)  

**Repurchase Rate**  
% of customers who purchased in a previous period and will buy in the next period.

**Customer Lifetime Value (CLV or LTV)**  
CLV is the ["present discounted value"](https://en.wikipedia.org/wiki/Present_value) of total profit that a customer is expected to yield. Different companies calculate this in different ways. To learn more about CLV, please review this [example](https://blog.kissmetrics.com/wp-content/uploads/2011/08/calculating-ltv.pdf) and this [chapter.](WDP-Fader-CustomerCentricity_Chapter4_CourseraCustomerAnalytics001.pdf)

<br>

Companies that sell merchandise on a subscription basis, such as Birchbox, are an increasingly popular variant of the basic e-commerce model. In this model, users prepay for regular delivery of merchandise. Often, the merchandise is curated by the company’s specialist curators instead of being selected by the user. Manufacturers may compensate or offer bulk discounts to the subscription e-commerce company for including the manufacturers' products in curated deliveries. For subscription companies, customer retention and and recommendation success metrics are especially relevant.

**Recommendation success rate**  
This is a category of metric which is heavily dependent on context. For example, Birchbox's recommendation success rate might be the percentage of items that each customer chooses to keep instead of return.

Software-as-a-Service (SaaS)
----------------------------

SaaS companies sell the right to use their software for a given time period, often on a recurring (subscription) basis but also sometimes on contracts with finite duration. There are many [B2B](https://en.wikipedia.org/wiki/Business-to-business) and [B2C](http://www.investopedia.com/terms/b/btoc.asp) SaaS companies, for example Salesforce, Oracle, Box, Asana, Evernote, and Dropbox. The SaaS model contrasts with the traditional software business model which sells a standalone copy of their software without establishing an ongoing relationship with the user.

Metrics about enrollment, engagement, and churn are key to understanding a SaaS company.

**Enrollment**  
 % of visitors that sign up for free trial or free version
 
**Engagement**  
Category of metric that describes how much users use the product
e.g. % of users who log in every day
e.g. number of tasks created (e.g. Asana)

**Conversion Rate (CVR)**  
% of of free users becoming paid users

**Revenue per customer / time period**  

**Churn**  
% of users canceling subscription in each period


Free Mobile App
---------------
Free mobile app businesses, like Zynga, earn revenue by displaying ads or offering paid features in a mobile app that is free to download. In the game Farmville, for example, users can purchase upgrades to make the game more interesting.

Mobile app developers focus on these metrics:

**Number of downloads**  

**Launch rate**  
% of customers who open the app after downloading (and create account)

**% or number of active users**  
those who use the app at least once every time period

**% of paid users**  
![](../images/percent_of_paying_users.png)  

**Time to first purchase**  
average duration between downloading and paying for something

**Churn**  
In mobile app context, churn can mean % who uninstall the app or haven't opened in a certain timeframe.


Media Site
-----

A media site provides its users content such as news articles or search results, and typically earns revenue from some combination of fees to access the content (e.g. subscription fee) and ads bundled with the content. The Wall Street Journal, Huffington Post, and Google Search are all examples of media sites.

This flowchart demonstrates how users generate revenue for a media site and related metrics.

![](../images/media_customer_lifecycle.png)
*Image credit: [Lean Analytics](http://leananalyticsbook.com/)*


User Generated Content
----------------------

User-generated content (UGC) sites are a subset of media sites, but they are different enough to warrant a separate discussion. UGC sites, such as Yelp, Facebook, and Twitch, bundle ads with content generated primarily by users. Engagement metrics, such as likes, shares, and posts, are key to understanding the health of a UGC business, and modeling the sometimes nebulous relationship between engagement and revenue is one of this business model’s central analytical challenges. Each UGC site has its own unique ways for users to engage, and a data scientist handling engagement metrics must understand the nuances behind each method of engagement in order to produce useful analyses.

An engagement funnel can be a useful way to understand the health of a UGC company:

![](../images/engagement_funnel.png)
*Image credit: [Lean Analytics](http://leananalyticsbook.com/)*

These are some metrics relevant to a UGC site:  
**Content Creation**  
e.g. number of new articles per day

**Movement through engagement funnel**  
e.g. % of people who "like" articles and then start writing articles

**Value of content**  
e.g. Ad impressions due to a single article or author

**Content sharing and virality**  
e.g. how content gets shared and drives growth


Two-Sided Marketplaces
----------------------

A two-sided marketplace brings together buyers and sellers of some good or service, and earns revenue from the buyer and/or the seller. These business can take on many different forms and operate in very different markets; Uber, AirBnB, Kickstarter, OkCupid, eBay, StubHub, Priceline, and Trulia are all two-sided marketplaces. Many companies combine traditional e-commerce with two-sided marketplaces. For example, Amazon sells its own inventory alongside that of other sellers on its platform. Economists sometimes call two-sided marketplace businesses "platform" businesses.

| Company           | Market               | Suppliers             | Demanders                         |
|-------------------|----------------------|-----------------------|-----------------------------------|
| Uber              | Transportation       | Drivers / Vehicles    | Riders                            |
| AirBnB            | Hotels               | Homeowners            | Travelers                         |
| Priceline         | Hotels               | Hotels                | Travelers                         |
| OkCupid           | Dates                | People who want dates | Other people who want dates       |
| Kickstarter       | Art / Products       | Artists / Builders    | Consumers of art / physical goods |
| Apple's App Store | Mobile Apps          | App developers        | Mobile users                      |
| Trulia            | Real estate listings | Real estate agents    | Prospective homebuyers            |
| Shopping Mall     | Retail goods         | Retail stores         | Shoppers                          |
| StubHub           | Event tickets        | Anyone with tickets   | People who want to attend an event|                       

These businesses face a "chicken-or-egg" problem when they're getting started. If there's no supply, there will be no demand, and vice versa. Uber has hired a handful of Towncar drivers in new markets by the hour to seed its platform with supply, until it could generate enough demand to attract more supply organically. Ticketing websites have been known to contract with sports teams and concert promoters to allocate supply to their platforms.
