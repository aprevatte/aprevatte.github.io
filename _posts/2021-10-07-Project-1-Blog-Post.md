2021-10-07-Project-1-Blog-Post
================
Alex Prevatte
10/7/2021

## Project 1 Findings

This project [COVID-19](https://aprevatte.github.io/COVID19-API/)
involved utilizing the COVID-19 API to construct contingency tables,
summary statistics, and data visualizations for countries with the
highest COVID-19 case count. I spent time writing functions that created
dataframes for users to easily see the confirmed cases and deaths for a
given region at any time. I then wanted to take a closer look at the
daily confirmed case count, instead of focusing on the cumulative sum of
cases which was provided in the API. This to me was important because I
wanted to understand the rate of growth or decline of cases over time.

After conducting exploratory data analysis, I thought it was interesting
that India, the second largest country by confirmed case count, had less
deaths than Brazil, the third largest country by case count. I also
found it interesting that the ‘recovered’ cases were 0 for every country
over time, which makes me believe that the data either wasn’t available
or there was an error in data collection. I was hoping to prepare a
report that displayed both COVID deaths and recoveries, but I ended up
changing my functions since there was not data for recoveries in the
summary endpoint.

The most difficult part of the programming was connecting with the
COVID-19 API and creating functions that worked for me. I have
experience generating summaries, plotting, etc. but I didn’t have a
whole lot of experience coming into this project with connecting to
APIs. After spending a fair amount of time on this project, I feel much
more comfortable extracting data from APIs and would enjoy doing it
again with other types of data.

If I were to approach a similar project again, I would spend time
writing out a plan of action for how I want to go about the analysis. I
went into this project actually wanting to use a different API, but
after reading the prompt more thoroughly, I had changed my mind. It’s
important to know that the direction you think that you are going in may
change after taking a closer look at the data. I had originally wanted
to incorporate the recoveries into my analysis, but I didn’t have much
data to work with so I decided against that route. I had a great
experience working on this project and I see myself in the future
wanting to performing my own data analysis on other APIs for my own
interest.
