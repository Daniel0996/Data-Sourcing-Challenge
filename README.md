# Data-Sourcing-Challenge
Module 6 Challenge - NOOA Geomagnetic Storms Prediction

## Introduction
This challenge aims to extract Geomagnetic Storms (`GST`s) and Coronal Mass Ejections (`CME`s) event data from NASA Open API for pace Weather Database Of Notifications, Knowledge, Information (`DONKI`).  Prepare both sets of data by expanding, cleaning and filtering using Python and Pandas libraries in Jupyter Notebook.  Finally, data for both events are merged and based on their reference to each other.  The final prediction analysis data is output to a csv file.

## Components
1. Part 1: Request CME data from the NASA API.

2. Part 2: Request GST data from the NASA API.

3. Part 3: Merge and Clean the Data for Export.

## Summary
Based on the prediction analysis data, the current `CME`- `GST` prediction is not accurate, and linking only 61 events in a 11-year period from 05/01/2013 to 05/01/2024.  Moreover, the time difference of linked `CME`- `GST` ranges between 1 days 08:36:00 and 6 days 03:00:00.

However, this preiction can serve as an early warning system for Geomagnetic Storms.  It can help powergrid operators and GPS system operators make necessary adjustments to mitigate the risk to the damage of their electronic equipments.