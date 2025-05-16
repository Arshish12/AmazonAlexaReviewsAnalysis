# 📊 Amazon Alexa Reviews Analysis

This project analyzes verified customer reviews of Amazon Alexa products using Python, pandas, and data visualization libraries. The goal is to uncover insights about customer satisfaction, review patterns, and product variation popularity.



## 📁 Dataset

The dataset contains the following fields:

- `variation`: Type/model of the Alexa product
- `verified_reviews`: Text of the customer review
- `rating`: Star rating (1 to 5)
- `feedback`: Binary sentiment (1 = positive, 0 = negative)
- `date`: Date of review


## 🎯 Objective of the Study

- Identify the most reviewed Amazon Alexa product variations.
- Analyze customer feedback and sentiment using review data.
- Explore the relationship between review length, feedback, and rating.
- Use visualizations to interpret customer satisfaction and engagement levels.


## 🧪 Methodology

1. **Data Preprocessing**
   - Handled missing values
   - Converted date to datetime format
   - Engineered new feature: `review_length` (word count per review)

2. **Exploratory Data Analysis**
   - Aggregated review stats by product variation
   - Generated descriptive statistics
   - Visualized top products by review count and average ratings

3. **Visualization Tools**
   - `matplotlib` and `seaborn` used for generating bar charts and insights


## 📈 Key Insights

- Certain Alexa product variations receive significantly more reviews.
- Average feedback and rating trends help identify customer satisfaction.
- Longer reviews tend to be more detailed and are useful in understanding user sentiment.


## 🛠️ Tools & Libraries

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook


