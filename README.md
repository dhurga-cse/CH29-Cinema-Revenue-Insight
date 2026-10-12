# Cinema Revenue Insight – CH29

## Project Overview
Cinema Revenue Insight analyzes cinema booking data to understand revenue patterns, ticket sales, occupancy, genre performance, showtime performance, cinema comparisons, and offer effectiveness.

## Objectives
- Analyze revenue across movie genres.
- Compare occupancy across showtimes.
- Compare weekday and weekend performance.
- Identify high-performing cinemas and offers.
- Study revenue trends across observation weeks.
- Explore machine-learning-based revenue prediction.

## Tools Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Microsoft Excel

## Dataset
This project uses **synthetic data created for analysis and demonstration**. It is not verified real-world cinema booking data.

The occupancy calculation uses a cinema-level capacity proxy because unique show-level capacity data is unavailable.

The `release_week` field represents the observation-period week, not a verified movie release week.

## Analysis
The project includes data cleaning, exploratory data analysis, grouped summaries, charts, and revenue prediction experiments.

## Machine Learning
A Random Forest regression model was explored to predict revenue. Model performance should be validated to ensure that target-derived or otherwise unavailable features do not cause data leakage.

## Project Status
Excel analysis and machine-learning experiments are included according to the files provided in this repository.
