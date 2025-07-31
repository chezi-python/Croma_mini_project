                                       iPhone Dataset Analysis Project
This project performs exploratory data analysis on a dataset of Apple iPhone models, including pricing, ratings, reviews, specifications, and discounts.

 Dataset
The dataset (iphone.csv) contains information on various iPhone models sold online, including:

Product name

MRP and Sale price

Star ratings (with some missing)

Number of ratings and reviews

RAM, Storage, and Color details

Objectives & Steps
🔧 Data Preparation
Clean column names by replacing spaces with underscores.

Handle missing values in the Star_Rating column:

First by using the average of all models.

Then using the average rating for phones with the same RAM.

Feature Engineering
Create a new column Discount_Percentage using MRP and Sale Price.

🔍 Data Insights
Identify the iPhone model with the highest discount.

Count total models by Storage size (e.g., 64 GB, 128 GB).

Count models by Color.

Count models by iPhone version (e.g., iPhone 8, iPhone XR).

Find Top 5 models with most reviews.

Calculate price range between highest and lowest MRP.

Find total reviews for iPhone 11 and iPhone 12.

Identify iPhone with 3rd highest MRP.

Compute average MRP of iPhones costing above ₹100,000.

Find 128 GB iPhone with highest rating-to-review ratio.
