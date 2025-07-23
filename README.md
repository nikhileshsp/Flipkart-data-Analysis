# Flipkart-data-Analysis

Flipkart Mobile Data Analysis
This repository provides a curated dataset of mobile phone listings from Flipkart alongside example scripts and notebooks for exploring and analyzing key product attributes such as ratings, pricing, discounts, and features. It’s ideal for data scientists and developers looking to practice real-world data cleaning, exploratory analysis, and visualization workflows.

Project Structure
data/flipkart_mobiles.csv
Raw CSV of mobile listings scraped from Flipkart, containing the following columns:

Name: model and variant name

Brand: manufacturer name

Ratings: average user rating (out of 5)

No_of_ratings: total number of user ratings

No_of_reviews: total number of written reviews

Product_features: list of key specifications

MSP: current selling price (₹)

MRP: original list price (₹)

Discount: percentage discount

notebooks/
Jupyter notebooks demonstrating:

Data ingestion and cleaning

Parsing and normalizing feature lists

Price vs. rating analysis

Brand-wise comparison of discounts and ratings

scripts/
Standalone Python scripts for:

Converting CSV to cleaned Parquet

Generating summary statistics

Exporting preprocessed data for modeling

