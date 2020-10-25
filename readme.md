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

-   [ ] Make data user interactive

    -   [ ] x-axis have the following demographics:

        -   [ ] In Poverty (%)

        -   [ ] Age (Median)

        -   [ ] Household Income (Median)

    -   [ ] y-axis have the following risk factors:

        -   [ ] Obese (%)

        -   [ ] Smokes (%)

        -   [ ] Lacks Healthcare (%)

    -   [ ] Add click events for each x and y label

    -   [ ] Animate the transitions for the circles’ locations

    -   [ ] Animate the transition for the ranges of the axes

-   [x] Incorporate d3-tip

    -   [x] Create a tooltip that expands on the data when the cursor hovers
        over the data point
