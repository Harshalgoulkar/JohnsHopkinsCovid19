Problem Statement

Task 1:- Prepare a complete data analysis report on the given data.
Task 2:- Fix a period for prediction of confirmed cases/deaths. Create a
predictive model to forecast the Covid19 cases based on past cases for a
specific country or region.
Task3:- Make suggestions to the government health department of the
country/region for preparation based on your predictions.

Dataset Description:
This is a daily updating version of COVID-19 Data Repository by the Center for Systems
Science and Engineering (CSSE) at Johns Hopkins University (JHU). The data updates
every day at 6am UTC, which updates just after the raw JHU data typically updates.
I&#39;m making it available in both a raw form (files with the prefix RAW) and convenient
form (files prefixed with CONVENIENT).
The data covers:
● confirmed cases and deaths on a country level
● confirmed cases and deaths by US county
● some metadata that&#39;s available in the raw JHU data

The RAW version is exactly as it&#39;s distributed in the original dataset.
The CONVENIENT version is aiming to be easier to analyze. The data is organized by
column rather than by row. The metadata is stripped out into a separate file. And it
converted to daily change rather than cumulative totals.
I have a notebook that updates just after each data dump updates, giving a brief
overview of the latest data. It&#39;s also a useful reference if you want to see how to read
the CONVENIENT data into a pandas DataFrame.

Domain: Healthcare

Model Comparison Report
Create a report stating the performance of multiple models on this data and
suggest the best model for production.