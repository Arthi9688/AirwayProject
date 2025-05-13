✈️ Airline Reviews Dashboard - Tableau Project
📊 Project Overview

This Tableau project analyzes airline passenger reviews using two datasets:

    Reviews Dataset – Contains detailed customer reviews of various airlines.

    Country Dataset – Maps countries to their respective regions and continents to allow geographic-level analysis.


🌐 View Dashboard Online

👉 Click here to view the live dashboard on Tableau Public
https://public.tableau.com/views/AirwayReviews_17470789231650/AirwayReviews?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Using these datasets, an interactive dashboard was developed in Tableau to explore and visualize average customer experience metrics across multiple dimensions.
🗂️ Data Description
1. ba_reviews.csv

Contains airline review data with the following columns:

    header, author, date, place, content

    aircraft, traveller_type, seat_type, route, date_flown

    recommended, trip_verified, rating

    Review Metrics: seat_comfort, cabin_staff_service, food_beverages, ground_service, value_for_money, entertainment

2. countries.csv

Contains geographic information:

    country, region, continent

📌 Dashboard Features

The Tableau dashboard presents a visual summary of airline review metrics with interactive features. Key components include:
✅ Key Metrics

A composite Metric Score was calculated based on the following numerical fields:

    rating, seat_comfort, cabin_staff_service, food_beverages, ground_service, value_for_money, entertainment

📈 Visualizations

    Average Metric by Month

    Average Metric by Country

    Average Metric by Aircraft and Reviews

🧩 Filters and Interactivity

Users can filter and explore the data using the following options:

    Month of Year

    Traveller Type

    Continent

    Metric

    Seat Type

    Aircraft

🛠️ Tools Used

    Tableau – Data visualization and dashboard creation

    CSV – Input data files for review content and geography mapping
