# Amazon_Vine_Analysis

## Overview of the analysis: 
We were hired by the start-up company Big Market as data analysts. This company has an important client, $ellby, who's about to release a larga catalog of products on a leading retail website. They asked Big Market to have a look at their products' reviews, compared to products sold by their competitors. Addittionaly, $ellby is interested in enrolling in a program that gifts free products to select reviewers but they are unsure if the cost is worth it. 

The first thing we have to work on is to translate word reviews into something our computers can work with, in order to deliver results. During this assignment, we get to prove the power of big data. 

## Results: 
We created multiple dataframes to visualize important data. In this case, we worked with the Health & Personal Care database. By scrolling through this section, you can have a look at parts of our analysis. 

Complete Dataframe
<img width="396" alt="Vine_DF" src="https://user-images.githubusercontent.com/88563922/149606495-444a4c3a-97e8-4676-bcc1-350039acaad0.png">

Dataframe filtered by products with > 20 votes
<img width="386" alt="Over 20 Reviews" src="https://user-images.githubusercontent.com/88563922/149606542-2432f809-bffc-4f87-b140-a5e289d514ea.png">

Dataframe filtered by Helpful Reviews
<img width="374" alt="Helpful Revies (2)" src="https://user-images.githubusercontent.com/88563922/149606548-61bb24a5-920b-4c58-bd7c-0c096b8e6758.png">

Product reviews made by Vine Reviewers
<img width="382" alt="Paid Reviews" src="https://user-images.githubusercontent.com/88563922/149606560-5facc7b9-3a6e-4103-8f0d-90ccf55b73e4.png">

Product reviews made by Non-Vine Reviewers
<img width="383" alt="Not Paid Reviews" src="https://user-images.githubusercontent.com/88563922/149606572-d6402857-337f-43a6-8c23-2eb41f36d11c.png">

### Data Summary
After analysing data, we created a summary to help us look at results easily. 
<img width="740" alt="Review Summary" src="https://user-images.githubusercontent.com/88563922/149606612-15f4efdd-1fba-4688-b244-a374407a1ab5.png">

Thanks to this summary table, we can answer the following questions:

 - How many Vine reviews and non-Vine reviews were there?
 There are 497 vine reviews and 120,863 non-vine reviews.
 
 - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 Out of all vine reviews, 220 had 5 stars. On the other hand, 74,470 non-vine  reviews had 5 stars.
 
 - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 44.27% of vine reviews were 5 stars and 61.62% of non-vine reviews were 5 stars. 
 

## Summary: 
According to our research, there is no positivity bias on this particular dataset (out of all category datasets that weren't analyzed). Thanks to our summary, we can see that non-vine reviews were much higher and had a higher percentage or 5-star grades that vine reviews. 
We recommend that one additional analysis we could do with the dataset is to use natural language processing (NLT) to better understand what clients like or dislike about products, and, what makes the difference between getting a 5-star rating or not. 
