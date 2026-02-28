Restaurant Market & Pricing Analysis

📌 Project Overview
This project performs end-to-end data cleaning and exploratory data analysis (EDA) on a restaurant dataset. The goal is to uncover insights related to pricing, customer ratings, location trends, and operational factors influencing restaurant performance.
The raw dataset contained inconsistencies such as mixed rating formats (e.g., "4.2/5"), missing values, and duplicate entries. These were cleaned and transformed into a structured format for analysis.

🎯 Objectives
Clean and preprocess raw restaurant data
Handle missing values and inconsistent formatting
Convert rating and cost columns into usable numeric format
Explore the relationship between pricing and ratings
Identify high-performing restaurant locations
Analyze the impact of online ordering and table booking
Examine rating consistency across major restaurant chains

🛠️ Tools & Technologies Used
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

🧹 Data Cleaning Process
The following transformations were performed:
Removed duplicate records
Handled missing values
Cleaned the rate column by removing “/5” and converting it to numeric
Converted cost_for_two to numeric format

Created new features:
high_rated (Rating ≥ 4.0)
cuisine_count
multi_cuisine category
These steps ensured the dataset was suitable for accurate analysis and visualization.

📊 Key Insights

Expensive restaurants do not necessarily receive higher ratings. Many affordable restaurants also maintain strong ratings.
Whitefield appears slightly more expensive than Koramangala, suggesting it may have relatively more premium dining options.
Offering online ordering does not significantly impact restaurant pricing.
Restaurants with more votes are not always rated higher. Popularity and quality do not consistently move together.
Indiranagar stands out as a strong dining hub, with the highest concentration of highly rated restaurants.
Allowing table booking does not noticeably increase customer engagement in terms of votes.
Even within well-known restaurant chains, ratings vary across branches, indicating that customer experience is not always consistent.
