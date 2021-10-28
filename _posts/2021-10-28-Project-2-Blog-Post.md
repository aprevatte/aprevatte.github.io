2020-10-28-Project-2-Blog-Post
================
Alex Prevatte
10/28/2021

## Project 2 Findings

This project [Online News
Popularity](https://chennadebrown.github.io/Project-2/) involved
analyzing the Online News Popularity data set from the UCI Machine
Learning Repository to construct predictive models on article shares by
topic. The repository for this project is located
[here](https://github.com/ChennadeBrown/Project-2).

Our team subsetted the data with parameters to automate Markdown reports
for each article topic. Then, we performed exploratory data analysis on
different quantitative and qualitative variables to observe any patterns
in the data. We then divided our data into a training and test set and
used linear regression, random forest, and boosted trees for predictive
modeling on article shares. Our models were selected using
cross-validation and were applied to the test sets. We conducted a
comparison among models and declared the winner as having the lowest
RMSE.

If I were to approach this project differently, I would make sure to
fork Chennade’s repository from the beginning. At one point in the
project, I accidentally overwrote some of her changes in Github.
Luckily, we were toward the end of the project and Chennade pushed her
current changes back up to Github. Also, I would work on the automation
of markdown reports during the data manipulation or subsetting stage.
After constructing all of our models, it took quite a long time to
render our document. This made it time consuming to fix errors, so this
was the most difficult part. My major takeaway from this project is that
automating markdown reports can be really useful for analysis and can
save time in the long run. For large data sets, I can see myself using
this technique for comparing candidate models among several categories.
