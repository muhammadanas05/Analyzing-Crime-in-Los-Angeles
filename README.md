![Los Angeles skyline](la_skyline.jpg)

Los Angeles, California 😎. The City of Angels. Tinseltown. The Entertainment Capital of the World!

Known for its warm weather, palm trees, sprawling coastline, and Hollywood, along with producing some of the most iconic films and songs. However, as with any highly populated city, it isn't always glamorous and there can be a large volume of crime. That's where you can help!

## Project Overview

This project involves analyzing a dataset of crime records from Los Angeles to uncover important insights that can aid in crime prevention and resource allocation. The analysis focuses on several key aspects:

1. Peak Crime Hour: Identifying the hour of the day with the highest frequency of crimes. This information can help the LAPD understand when criminal activity is most prevalent.

2. Peak Night Crime Locatio: Determining which area of Los Angeles has the highest frequency of night crimes (crimes committed between 10 PM and 4 AM). This helps in targeting resources and patrols to areas with high night-time criminal activity.

3. Victim Age Distribution: Analyzing the age distribution of crime victims. Understanding which age groups are most affected by crime can guide preventive measures and support services for those specific demographics.

## The Data

The dataset provided for this analysis is `crimes.csv`. It includes the following columns:

- `DR_NO`: Division of Records Number - A unique file number for each record.
- `Date Rptd`: The date the crime was reported.
- `DATE OCC`: The date the crime occurred.
- `TIME OCC`: The time the crime occurred, in 24-hour military format.
- `AREA NAME`: The name of the area or patrol division where the crime occurred.
- `Crm Cd Desc`: Description of the crime committed.
- `Vict Age`: Age of the crime victim.
- `Vict Sex`: Gender of the victim (`F` for Female, `M` for Male, `X` for Unknown).
- `Vict Descent`: Descent of the victim, coded into various categories.
- `Weapon Desc`: Description of the weapon used (if applicable).
- `Status Desc`: Status of the crime.
- `LOCATION`: Street address of the crime.

## Objectives

1. Peak Crime Hour: Determine the hour with the highest frequency of crimes to understand peak crime times.

2. Peak Night Crime Location: Identify the area with the highest number of night-time crimes to focus resources effectively.

3. Victim Age Distribution: Analyze and categorize crime victims into age groups to identify which demographics are most affected.

## Getting Started

1. Ensure you have the necessary libraries installed: `pandas`, `numpy`, `matplotlib`, and `seaborn`.

2. Load the `crimes.csv` dataset and perform the analysis as described.

3. Interpret the results to provide actionable insights for the LAPD.

## Results

- Peak Crime Hour: The hour with the highest frequency of crimes.
- Peak Night Crime Location: The area with the most frequent night-time crimes.
- Victim Ages: Distribution of crimes across different age groups.
