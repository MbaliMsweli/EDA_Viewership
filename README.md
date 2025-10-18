# Viewership Analysis — Bright TV 

# Introduction
Bright TV recently began a new data initiative to better understand audience engagement and improve content performance across different platforms.
I conducted a comprehensive analysis of the company’s viewership data to uncover insights into viewer behavior, top-performing platforms, most-watched content, and viewing patterns over time.
This project leverages Python (Pandas & Matplotlib) and Excel to clean, analyze, and visualize viewing data for data-driven decision-making.

# Problem Statement
Over the past months, Bright TV struggled to understand audience engagement due to the lack of structured data analysis.
The content and marketing teams relied on assumptions and manual reports, which made it difficult to identify which platforms or programs performed best.

As a result:

Viewer engagement dropped across multiple platforms.
The company could not determine when audiences were most active.
High-performing shows were not being promoted strategically.
Management had limited visibility into platform-specific performance and audience preferences.

# Aim
The aim of this project is to analyze Bright TV’s viewership data to help management make data-driven decisions about audience engagement and content strategy.
The focus is on identifying:

## The most popular platforms and titles.
The busiest viewing days and time periods.
The overall watch-time trends across different platforms and events.
Insights from this analysis will guide Bright TV in optimizing programming schedules, improving platform engagement, and increasing overall viewer retention.

# Objectives
To achieve the project aim, the following key steps were taken:

## Data Collection & Preparation
Gathered viewership data containing DateID, Platform, PlayEventType, VideoTitle, CustomerID, and TotalTimeWatched.
Loaded and cleaned the dataset in Python using Pandas.

## Data Cleaning & Transformation
Converted columns into appropriate data types (e.g., DateID → date).
Removed duplicates and missing values.
Created new columns such as DayOfWeek to enable time-based analysis.

## Exploratory Data Analysis (EDA)
Examined viewing patterns by platform, event type, and video title.
Identified the top 5 most-watched titles.
Aggregated total watch time per day to uncover time-based trends.

## Visualization & Insights
Created bar charts, pie charts, and line graphs using Matplotlib to display trends.
Analyzed watch-time distribution by platform, title, and event type.
To address these issues, the company launched a Viewership Analysis Project aimed at transforming raw data into clear insights that guide programming, scheduling, and marketing strategies.
