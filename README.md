# 🏘️ Real Estate Listings Analysis
## Research Project: Apartment Sale Listings
## 🎓 What Is This Project?
Congratulations! You’ve completed the course in the simulator. Now it’s time to put your knowledge into practice by solving an analytical case. You’ll work on this project independently.

Once you finish, submit it for review. Within 24 hours, you’ll receive feedback. You’ll need to revise your project based on the comments and resubmit it.

It’s likely you’ll receive additional feedback — that’s perfectly normal. The revision process may go through several stages.

The project is considered complete once all corrections are approved.

## 📌 Project Description
You have access to data from Yandex Real Estate — an archive of apartment sale listings in Saint Petersburg and nearby localities over several years. Your goal is to learn how to determine the market value of real estate properties.

Your task is to identify key parameters. This will help build an automated system to detect anomalies and fraudulent activity.

Each apartment listing contains two types of data:

- User-entered information

- Automatically generated data based on mapping services (e.g., distance to city center, airport, nearest park or body of water)

## 🛠️ Instructions
Step 1: Open the data file and explore the general information
File path: /datasets/real_estate_data.csv. Download the dataset.

Step 2: Data Preprocessing
Identify and examine missing values:

- Some missing values can be logically filled. For example, if the number of balconies is not specified, it likely means there are none. These should be replaced with 0.

- For other types of data, there may be no appropriate replacement. In such cases, it’s best to leave them blank — missing values can be meaningful signals.

Fill in missing values where appropriate. Explain why you chose to fill in those specific columns and how you selected the replacement values.

List possible reasons for missing data.

Convert data to appropriate types:

- Explain which columns need type conversion and why.

Step 3: Calculate and add the following to the table:
- Price per square meter

- Day of the week, month, and year the listing was published

- Apartment floor category: first, last, or other

- Ratio of living area to total area, and kitchen area to total area

Step 4: Perform Exploratory Data Analysis and Follow Instructions
Study the following parameters: area, price, number of rooms, ceiling height. Create histograms for each.

Analyze the time it takes to sell an apartment. Create a histogram. Calculate the mean and median. Describe how long sales typically take. Define what counts as a very fast or unusually long sale.

Remove rare and outlier values. Describe any patterns or anomalies you discover.

Identify which factors most influence apartment prices. Explore whether price depends on:

- Area

- Number of rooms

- Distance from the city center

- Floor category (first, last, other)

- Listing date (day of the week, month, year)

Select the 10 localities with the most listings. Calculate the average price per square meter in each. Identify the localities with the highest and lowest housing prices. Use the locality_name column for this.

Study apartment listings with distance to the city center. Focus on listings in Saint Petersburg (locality_name). Your task is to determine which area is considered the city center.

- Create a column with distance to the center in kilometers (rounded to whole numbers)

- Calculate the average price for each kilometer

- Plot a graph showing how price depends on distance from the center

- Identify the point where the graph changes significantly — this will define the central zone

Highlight the segment of apartments located in the center. Analyze this area and study the following parameters:

- Area

- Price

- Number of rooms

- Ceiling height

Also identify factors that influence apartment prices (number of rooms, floor, distance from center, listing date). Draw conclusions. Compare them to the overall findings from the full dataset.

Step 5: Write a General Conclusion
Formatting: Complete the assignment in Jupyter Notebook. Use code cells for programming and markdown cells for explanations. Apply formatting and headings.

📋 Data Description
- airports_nearest — distance to the nearest airport (in meters)

- balcony — number of balconies

- ceiling_height — ceiling height (in meters)

- cityCenters_nearest — distance to city center (in meters)

- days_exposition — number of days the listing was active

- first_day_exposition — listing publication date

- floor — apartment floor

- floors_total — total number of floors in the building

- is_apartment — whether it’s an apartment (boolean)

- kitchen_area — kitchen area (in square meters)

- last_price — price at the time of listing removal

- living_area — living area (in square meters)

- locality_name — name of the locality

- open_plan — open floor plan (boolean)

- parks_around3000 — number of parks within 3 km

- parks_nearest — distance to the nearest park (in meters)

- ponds_around3000 — number of bodies of water within 3 km

- ponds_nearest — distance to the nearest body of water (in meters)

- rooms — number of rooms

- studio — whether it’s a studio apartment (boolean)

- total_area — total area (in square meters)

- total_images — number of photos in the listing

✅ How Will My Project Be Evaluated?

We’ve prepared evaluation criteria. Review them carefully before starting.
Reviewers will pay attention to:

- How you describe problems found in the data

- Which methods you use to handle missing values

- How you use data slicing

- Whether your graphs solve specific analytical tasks

- Which graphing methods you apply

- Whether you summarize final data in pivot tables

- Whether you automate graph generation

- Whether you calculate and correctly interpret relationships in the data

- Whether your project is well-structured and your code is clean

- What conclusions you draw

- Whether you leave comments explaining your steps

Everything you need to complete this project is in your cheat sheets and course notes.

Good luck! 🍀
