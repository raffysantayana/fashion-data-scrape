# An Analysis of Male Fashion Trends

![image](/images/coverimage.jpg)

## Problem Statement
After spending three months self-isolating myself and living nearly every day in sweats, it is difficult to understand what the direction that fashion is going. I have not dressed up frequently enough to say that my tastes have changed and I have not seen others in public to take new inspiration from. So which trends have died or are dying and what are the new trends that people like? Since it feels weird for me to go to Twitter and start a thread for people to post pictures or videos of them dressing up, I'll use my data skills to solve this problem.

## Executive Summary
### Data Gathering
When thinking about how to determine which trends are dying and which trends are on the rise, I figured that this seems similar to the rate of population growth. If there are more people passing away than people being born, then population rate should decrease and vice versa. So if people are putting their clothes up for sale on sites like Poshmark, then one may consider those pieces to be out of style. When scraping, I will sort by most recent postings because something posted 10 days ago are most likely to be a less favorable trend than something that was posted 10 minutes ago.

As for upcoming or rising trends, we can look at sites such as Ralph Lauren and sort by Best Selling. Ideally, I would want a "Sold Recently" and see which items are being sold in real time since that seems to be more similar to the scrape on Poshmark's data, but this aggregate of Best Selling items seems like the next best option.

### Analysis
To analyze the data, I will perform cluster analysis to see which groups of fashion trends there are.
I hope to scrape data such as:
- __type of clothing__ that will tell me if the item is a baseball cap, beanie, jeans, khakis, etc.
- __color(s)__ that may be able to tell me which color paterns are on the rise.
- __price__ may tell me what people expect the depreciation value of their items are. Will be difficult since I do not know when people on Poshmark bought the pieces they are selling.

## Assumptions
Coronavirus and social distancing may be affecting the rate at which people are posting sales. I can understand that there would be a rise of people selling their clothes because they feel they don't need muchclothes anymore since they expect COVID to last a long time.
Also, I am assuming that sites that sort items by Best Selling or Trending do not manipulate these sorts at all. Who knows if the brains behind the site are actually promoting items that need a bit of a boost in sales.
