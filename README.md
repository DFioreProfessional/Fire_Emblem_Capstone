# Fire Emblem Poll Analysis Breakdown

## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Challenges](#problems-and-challenges)
* [Technologies Used](#technologies-used)
* [Sources](#sources)

## Motivation:
= I chose to work on this project because Fire Emblem is one of my favorite game series, and because it is one that has shown remarkable growth over the years in large part due to the change in marketing strategies. I wanted to look at the yearly popularity polls and see what roll, if any, they played in making these new decisions.

## Questions:
I wanted to answer the following questions.
1) How did the results of the first poll impact the direction of the series going forward?
2) What can the results of the following polls teach us about the importance of community feedback?
3) Based on the results of the most recent poll, what can we guess Nintendo might do next with this franchise?

## Acquiring and Normalizing the Data
- The results of the Choose Your Legends popularity polls are publicly available on Nintendo's website. I pulled down the data directly from there, and then cross referenced my data against research done by other people on the same subject.
- Sales data from Nintendo is notoriously difficult to acquire, I pulled the information from the Video Game Sales Fandom Wiki which estimates the values based on financial reports from Nintendo, but we only need to look at it for a few generalized reference points.

## Problems and Challenges 
- I had a great deal of trouble trying to find a more credible source for the sales data, unfortunately Japanese companies don't report financial information in ways that are easy to acquire overseas, and Nintendo especially can be very obscure with the information in regards to anything other than their biggest names (I.E. Mario, Zelda, etc.)
- I did spend too much time cleaning and making the data look good when I didn't actually wind up using a lot of the information. 

## Technologies Used
1) Excel - to consolidate and clean the data
2) SQL via pgAdmin 4 - to compare the data and explore how I would go about presenting it
3) Power BI - to create the final graphs and assemble the presentation
4) Git - version control 

## Data Sources

1) poll data scraped from [this website](https://vote9.campaigns.fire-emblem-heroes.com/en-US/index.html)
2) financial data pulled from [this website](https://www.vgchartz.com/game/228816/fire-emblem/)# Fire_Emblem_Capstone
