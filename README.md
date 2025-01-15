# NASA Geomagnetic Storm (GST) and Coronal Mass Ejections (CME) Data Analysis

## Goal

The goal of this project is to analyze the relationship between **Geomagnetic Storms (GSTs)** and **Coronal Mass Ejections (CMEs)** using data from NASA's **DONKI API** (The Space Weather Database Of Notifications, Knowledge, and Information). The project involves retrieving GST and CME data, processing and cleaning it, and computing the average time it takes for a CME to cause a GST. 

## Problem

GSTs are disturbances in the Earth's magnetosphere caused by solar activity, such as solar flares or CMEs. Understanding the relationship between CMEs and GSTs is critical for space weather forecasting and understanding how solar activity impacts the Earth's environment. Specifically, it is important to understand how much time elapses between the start of a CME and the occurrence of a GST.

This project aims to answer the following question:
- What is the average time difference between the occurrence of a CME and the start of a GST?

## Key Findings

The analysis of the relationship between CMEs and GSTs has revealed the typical time differences between the two phenomena. By computing the mean and median time differences, we can gain insight into how long it generally takes for a CME to trigger a GST. The calculations of standard deviation also provides the spread of data and insight into the variability.

## Challenges

During execution, I faced memory-related issues in Python where previous runs affected the current session, requiring multiple environment resets. Additionally, GET requests to the NASA API for CME data took about 4-5 minutes, which impacted the overall runtime. To mitigate this, I processed the data in smaller chunks and managed memory usage to avoid overloads.

## Conclusion

This project provides an essential first step toward understanding the relationship between solar activity and its impact on the Earth's magnetosphere. The data processed and analyzed can be used for further research into solar weather patterns and their effect on communication, navigation, and satellite operations.

By leveraging NASA's DONKI API, we've created a pipeline for accessing and analyzing space weather data that can be adapted for future studies.

## Resources

- NASA DONKI API Documentation
- Pandas Documentation
- Python Documentation
- Tutoring
- Ask BCS
- Office Hours
- Open AI
