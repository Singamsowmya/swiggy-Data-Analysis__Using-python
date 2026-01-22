# swiggy-Data-Analysis__Using-python
README

📊 Swiggy Data Analysis Using Python

This project performs exploratory data analysis (EDA) on Swiggy restaurant data using Python libraries such as pandas, numpy, matplotlib, and seaborn. The analysis helps in understanding trends in restaurant ratings, online orders, cost for two, and popularity based on the number of votes.

🧹 Data Preprocessing :

Converted ratings from "x/y" format (e.g., 4.1/5) to float values. Handled missing values and verified data types. Ensured consistency in categorical features like online_order, book_table, and listed_in(type).

📊 Visualizations and Analysis :

Count Plot of Restaurant Types :Showed distribution of restaurants by type (listed_in(type)).

Votes per Restaurant Type : Grouped data by listed_in(type) and plotted total votes using a line graph.

Restaurant with Maximum Votes : Identified "Empire Restaurant" as the one with the highest number of votes.

Online Order Distribution : Count plot of whether restaurants offer online ordering.

Rating Distribution : Histogram of restaurant ratings to understand their spread.

Cost for Two : Count plot of approx_cost(for two people) to analyze pricing trends.

Boxplot(Online Order vs Rating) : Analyzed if offering online ordering affects ratings.

Heatmap : Created a pivot table of restaurant types vs online order availability. Visualized with a heatmap to identify the relationship between the two.

📦 Requirementsc :

Install the following libraries before running the notebook:

pip install pandas numpy matplotlib seaborn

▶️ How to Run :

Clone this repository or download the notebook and dataset.
Ensure the dataset CSV file is correctly placed and the path is updated.
Run the notebook in Jupyter or any Python IDE.
📈 Sample Output :

Highest voted restaurant: Empire Restaurant
Most common restaurant types: Buffet, Cafes, etc.
Online ordering has a slightly positive correlation with higher ratings.
📌 Conclusion :

This project gives an overview of customer preferences, restaurant popularity, and pricing strategy using simple but effective visualizations. It provides useful insights into restaurant performance on Swiggy.

📚 Future Improvements :

Add sentiment analysis using customer reviews (if available).
Predict restaurant ratings using machine learning models.
Perform geographical analysis based on city or locality.
