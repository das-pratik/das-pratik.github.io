---
layout: post
title: "Search n' Recommend"
date: 2020-10-20
tags: recommender search information-retrieval
---

Understanding the significance of internet’s distribution engines - search and recommendation, requires a refresher on how commerce (and media distribution) took place pre-internet and the rapid technological evolution in the last 30 years of internet proliferation.
<br/>
<br/>
<div class="grid-container">
    <img src="{{site.baseurl}}/images/search-n-recommend-05.png" alt="No Image">
</div>
<br/>
<br/>
The 1950-60s were the age of mass consumerism and mass media; P&G and Coca Cola captured the then-modern consumer’s mindset. They built their vast value chains by building strong processes around R&D,  manufacturing, branding and distribution. Integrating these functions well was key to winning in the marketplace - a battle of customer attention and customer choice fought in TV screens and on shelf spaces. 
<br/>
<br/>
While TV screens mass propagated the values of the brand to everyone watching and initiated ‘Attention’ stage, it was the shelf space at the neighborhood supermarket that ferried the customer across the entire AIDA funnel. It was here that a customer got to engage with the brand better and /interact/ with the its products.

---
<br/>

Come 1970s and the technical progress that followed in computing and communication, commerce and media upstarts started monetizing customer’s attention. Cable companies such as Comcast, TCI, etc. were able to build strong ‘localized’ moats by bundling broadcast television channels and delivering superior TV experience via cable to customers. Bundling benefitted both network and customers and the cable companies enjoyed the advantages from economies of scale.
<br/>
<br/>
In commerce, Walmart came along and built an empire by optimizing the problem of ‘/determining the right assortment for the finite shelf space at the lowest price everyday/’ for the customers at a store. As the largest buyer, Walmart over time could dictate pricing terms with its suppliers.
<br/>
<br/>
Both Walmart and cable companies enjoyed their success by building a moat around customer touch point. Personalization was still at a zip-code/DMA level - where one Cable station or one Walmart store could maintain dominant position. Marketing had transitioned from a Mad-men style arcane art to nerdy pricing models run by statisticians.
<br/>
<br/>
Till now, a customer’s attention was a finite resource - limited by TV ad slots and self space. The internet upended both - the limited shelf space with its limited assortment at your nearest Walmart gave way to an infinite assortment of products visible by scrolling infinitely on your mobile screen. The distribution battleground had shifted from physical inventory (atoms) to information (bits).
<br/>
<br/>
Methods of information distribution and retrieval have evolved significantly over internet’s 30-year history. Version 1 was the curated media pioneered by Yahoo! in early 1990s. This technology relied on human operators curating internet pages and creating a directory. 
<br/>
<br/>
Search engines started showing up in late 90s when manual curation of information soon became costly. User advanced search functionalities, Amazon opened up the ‘everything’ store to customers - A shopper was no longer constrained by items on shelves at the nearest supermarket; she could now scroll and browse the everything catalog.

---
<br/>
Recommenders still played a supporting role to the more dominant search functionality. Search was the promise of delivering a one-stop storefront to an infinite inventory of content -  books (Amazon web bookstore released in 1995), DVDs (Netflix launched DVD rental website in 1998), and digital music (iTunes released in 2001). 
<br/>
<br/>
Tech Cos started hitting the /limits of search technology when the rate of content creation surpassed the rate of accurately classifying and tagging inventory/. The internet bubble witnessed the creation of marketplaces of commodities of all shapes and sizes. Soon the frontier of customer need has shifted - from /serving all the information to a customer/ to /delighting customers with contextual information/.
<br/>
<br/>
Recommender’s took the center stage when Netflix released the much publicized ([Netflix Prize](https://www.netflixprize.com)) in 2006 and awarded the winner $ 1M for beating the champion recommender in 2008. The early pioneers of RecSys systems defined context by mining customers’ transactions or explicit behavior (purchase and clicks) and identifying patterns across customers (collaborative filtering) or across content (content-based filtering) to formulate a recommendation.
<br/>
<br/>
New business models and technology vastly expanded the scope of what content could be. Media content consumers could now interact with one another and create their own content. ‘User generated content’ platforms such as yelp, Instagram, Twitter, etc. opened internet’s floodgates. 

---
<br/>
RecSysv1.0, which identified customer X customer or content X content similarities, worked well when the content inventory ( of books or DVDs)  ‘moved’ slowly. ( number of movies released in a year is on a scale of 1000s, and books on a scale of 100,000s). 
When platforms opened up to UGCs (YouTube) and expanded to new countries with different languages, different preferences and lingual characteristics, the content became more ‘dynamic’. 
<br/>
<br/>
The ruleset created using RecSys v1.0 could not apply to this new form of content. The problems with RecSys v1.0 were from its closed loop design and its adverse side-effects - filter bubbles and echo chambers. Such a system over time would converge towards a fixed set of recommendations (or making the recommendations /stale/) 
<br/>
<br/>
<div class="grid-container">
    <img src="{{site.baseurl}}/images/search-n-recommend-01.png" alt="No Image">
    <img src="{{site.baseurl}}/images/search-n-recommend-02.png" alt="No Image">
</div>
<br/>
<br/>
New developments in RecSys started addressing these problems by implementing one or both these designs. By adding back randomness (explore) and new trends ( from search terms), these architecture de-bias the model training process. 
<br/>
<br/>
<div class="grid-container">
<img src="{{site.baseurl}}/images/search-n-recommend-03.png" alt="No Image">
<img src="{{site.baseurl}}/images/search-n-recommend-04.png" alt="No Image">
</div>
<br/>
<br/>
Recommenders are now being applied in novel ways  - by tightly integrating them with offline business functions and UX design - and across different content formats. From recommending apparel (Amazon vs. Stitch Fix), digital music (iTunes vs. Spotify), and short-form videos (Youtube vs. Tik Tok). 
<br/>
<br/>
RecSys v3.0 needs to solve for Transparency, Fairness, Explainability and Trust.