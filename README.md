# Udacity Capstone Project

## Project Overview

For the final capstone, Starbucks offer synthetic data to be analysed for useful insights. As such, we were given free rein on the direction we wanted to take, and I decided to focus on the general data cleaning process, and how well one can work with such data.

## Problem Statement
There were 2 questions I set answer through this project.
1. In data engineering, just how much engineering do you need, and when should you stop?
2. Is sythetic data reliable for simulations and predictions?

## Metrics
While like most data scientists, I love the modeling and predictions, but sadly, that was not the approach I took with this analysis. Instead I chose to focus on the aggregation and resulting visual.

## Data Exploration
In looking at the data, 3 different data sets were provided:

* portfolio.json
* profile.json
* transcript.json 

And while for the most part they didn't pose a problem, in the transcript data, the value variable which contained dictionaries as the values had significant inconsistencies. The `offer id` was present in two forms `offer_id` and `offer id`, which in a dataset of over 340,000 rows, poses a problem when trying to access each dictionary's value.

Another observation made was on the sparseness of the `offer_completed` varible. 

## Data Visualization

![](https://www.github.com/ENHarry/Capstone/blob/master/images/sum_offers_completed.png)

The visualizations is shows the top ten offer completions by users. It is odd that out of the 10 offers offered to users, a large portion took advantage of only 6 of those offers.

## Conclusion
A different approach needs to be taken.
