Data Journalism
===============

Description
-----------

Time to analyze trends across the lives in the US by creating an interactive d3
chart of census data.

The goal is to identify health risks facing particular demographics. The data
set is based on 2014 ACS 1-year estimates. The data set includes data on rates
of income, obesity, poverty, etc. by state.

 

Requirements
------------

-   [x] Initial Scatter Plot

    -   [x] Initialize x-label to Poverty and y-label as Healthcare

    -   [x] Load data.csv using d3

    -   [x] Append the aces and labels onto the left and bottom of the chart

    -   [x] State Abbreviations in circles

-   [x] Make data user interactive

    -   [x] x-axis have the following demographics:

        -   [x] In Poverty (%)

        -   [x] Age (Median)

        -   [x] Household Income (Median)

    -   [x] y-axis have the following risk factors:

        -   [x] Obese (%)

        -   [x] Smokes (%)

        -   [x] Lacks Healthcare (%)

    -   [x] Add click events for each x and y label

    -   [x] Animate the transitions for the circles’ locations

    -   [x] Animate the transition for the ranges of the axes

-   [x] Incorporate d3-tip

    -   [x] Create a tooltip that expands on the data when the cursor hovers
        over the data point
