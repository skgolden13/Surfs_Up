# Surfs Up

## Project Overview

W. Avy has requested weather data analysis before investing in a Surf n' Shake shop on Oahu, Hawaii. An earlier investment in a similar project without weather analysis closed down early because of significant rainfall in that region. W. Avy has provided an SQLite Database containing temperature and precipitation data from Oahu.

This analysis was performed using Jupyter Notebook, Python, SQAlchemy, and SQLite.

## Analysis Results

There are three main differences between the temperature statistics for June and December:
- More temperature readings were taken in June than in December
- The average temperature in June was roughly 4 degrees Fahrenheit higher than in December
- December had a larger standard deviation for temperatures than June

The summary statistics for June and December can be found below in Figures 1 and 2 respectively.

<br/>

<p align="center">
  <img width="200" alt="June_Temperature_Statistics" src="https://github.com/skgolden13/Surfs_Up/blob/main/June_Temperature_Statistics.PNG"><br/>
  Figure 1: Summary Statistics for Temperature in June
</p>

<br/>

<p align="center">
  <img width="200" alt="December_Temperature_Statistics" src="https://github.com/skgolden13/Surfs_Up/blob/main/December_Temperature_Statistics.PNG"><br/>
  Figure 2: Summary Statistics for Temperature in December
</p>

## Analysis Summary

With the temperatures being similar for June and December, the Surf and Shake shop would likely be able to operate year round on Oahu. To address W. Avy's concerns about precipitation, additional queries should be run for the precipitation in June and December. It would also be useful to look at weather data from later in the winter, such as February, and later in the summer, such as August, to get a better picture of the weather on Oahu year-round.
