# Project Proposal for The Data Incubator

Project Title: Who Invents America?

Motivation: More than 30,000 patents out of are granted in 2018 by the United States Patent and Trademark Office (USPTO), adding to the pool of 300,000 valid patents. The ratio of patents granted among those applied, however, is less than 50% for the first year, 60 percent for the second year, and 70% percent for the third year after application, implying considerable risks for inventors to make business decisions such as overhead investments, financing terms and competition strategies. This project aims at developing a product that help inventors (or competitors) predict the probability of patents being granted and the time the granting process takes, so that they can adjust their business operations accordingly. 

Data Source: 

Public PAIR from USPTO (https://www.uspto.gov/learning-and-resources/electronic-data-products/patent-examination-research-dataset-public-pair)

This database contains detailed information on 9.2 million publicly viewable patent applications filed with the USPTO. The data sets that I use in this project are application data, inventor data, and status codes.


Analysis:

Comparing the total number of patents granted by origin of inventors within the US, we can see that California residents receive the largest number of patents, followed by Texas, Washington, and states around the Great Lakes. The “fly-over” states receive the least patents. However, if we consider patents granted per thousand residents, while California is still among the most innovative, Washington, Oregon, Idaho are actually as competitive. Vermont and New Hampshire, although small in population, leads the US in per capita patent granted.

The median time from application to grant decrease year by year in the last decade, from 1232 days in 2010 to 821 days in 2017. 

Moving forward, I will use logistic regressions to predict whether a patent application is likely to be approved within three years and a Tobit model to predict the expected length of patent granting process.
