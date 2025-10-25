*Amazon Top 50 Bestselling Books Analysis (2009-2019)*

A comprehensive data analysis exploring trends, patterns, and insights from Amazon's bestselling books over a decade. This project examines 550 books to uncover what factors contribute to success in the competitive book market.


**🎯 Quick Start**


• Clone or download this repository

• Install dependencies: pip install pandas matplotlib seaborn scikit-learn scipy jupyter

• Open decade_of_amazon_top_50_books.ipynb and run the cells sequentially

• View visualizations and findings generated throughout the notebook


**📊 Project Overview**


This analysis examines the top 50 bestselling books on Amazon for each year from 2009 to 2019, investigating how ratings, pricing, and reader engagement evolved across the decade. The dataset includes 550 unique books from 248 authors across both fiction and non-fiction genres.

***Research Questions:***

• How do book ratings, prices, and review volumes change over time?

• Are there differences between fiction and non-fiction bestsellers?

• What correlations exist between price, ratings, and reader engagement?

• Can we predict book success from these metrics?


**🔍 Key Findings**


***Rating Trends:***

Bestseller ratings remained exceptionally high and stable, averaging 4.62 stars across all 550 books. Notably, ratings improved by 0.16 points from 2009 to 2019, suggesting that customer expectations for top books have increased over the decade.

***Price Dynamics:***

Average book prices declined significantly from approximately $18.42 in 2009 to $13.10 by 2019—a reduction of $5.32. Despite this decline, 12.4% of bestsellers were premium titles exceeding $20. Interestingly, price showed only a weak negative correlation with ratings (-0.133), indicating that higher prices don't guarantee better reviews among bestsellers.

***Reader Engagement:***

The most reviewed book was "Where the Crawdads Sing" by Delia Owels with 87,841 reviews and a 4.80 rating. On average, bestsellers received 11,953 reviews. However, review volume showed minimal correlation with ratings (-0.002), suggesting that popularity in terms of volume doesn't necessarily mean higher quality ratings.

***Genre Comparison:***

Both fiction and non-fiction achieved strong bestseller status. Fiction books (43.6% of the dataset) averaged 4.65 stars and 15,684 reviews but at lower prices ($10.85 average). Non-fiction titles (56.4%) averaged 4.60 stars with 9,065 reviews at higher prices ($14.84 average).


**📈 Dataset Details**


• ***Total Books:*** 550 (Top 50 per year)

• ***Time Period:*** 2009-2019

• ***Unique Authors:*** 248

• ***Genres:*** Fiction and Non-Fiction

• ***Total Reviews Across Dataset:*** 6,574,305

• ***Rating Range:*** 3.30 - 4.90 stars

• ***Price Range:*** $0.00 - $105.00




**🛠️ Technical**


• ***Python 3.x*** - Core analysis language

• ***Pandas*** - Data loading, cleaning, and manipulation

• ***Matplotlib & Seaborn*** - Data visualization and plotting

• ***Scikit-learn*** - Predictive modeling and regression

• ***SciPy*** - Statistical analysis and correlations

• ***Jupyter Notebook*** - Interactive analysis environment



**📁 Project Structure**


amazon-top-50-books-analysis/

├── a_decade_of_amazon_top_50_books.ipynb                        # Main analysis notebook

├── data/

│   └── bestsellers.csv                                          # Dataset (2009-2019)

├── visualizations/                                              # Generated plots and charts

├── README.md                                                    # This file

└── requirements.txt                                             # Dependencies



**💾 Data** 


The dataset contains publicly available Amazon sales data compiled from Kaggle: Amazon Top 50 Bestselling Books (2009-2019)

Download the dataset and place bestsellers.csv in the data/ folder before running the notebook.



**📊 Analysis Sections**


***Exploratory Data Analysis:*** 
Distribution of ratings, prices, and reviews with summary statistics and data quality checks.

***Temporal Trends:*** 
Year-over-year changes in average ratings, prices, and review counts to identify long-term market shifts.

***Genre Comparison:*** 
Statistical comparison between fiction and non-fiction bestsellers across all metrics.

***Correlation Analysis:*** 
Relationship mapping between price-rating, review volume-rating, and time-based trends.

***Predictive Modeling:*** 
Linear regression model to predict ratings from price, review count, and genre (R² = 0.074).

***Business Insights:*** 
Actionable recommendations for publishers, authors, and retailers based on findings.



**⚠️ Important Limitations**


***Sample Bias:*** 
This analysis only includes bestselling books, not representative of the broader publishing market.

***Survivorship Bias:*** 
All analyzed books have already "succeeded"—findings cannot predict which new books will become bestsellers.

***Platform-Specific:*** 
Amazon data only; trends may differ on other retail platforms.

***Time Period:*** 
Data spans 2009-2019; the publishing market has evolved since then, particularly post-2020 with digital expansion.

***Genre Simplicity:*** 
Categorization limited to Fiction/Non-Fiction, missing granular sub-genre insights.




**🎓 Recommendations**



***For Publishers:*** 

• Diversify portfolios across both genres. 

• Price optimization matters less than quality for top-performing titles. 

• Invest in sustained reader engagement strategies.


***For Authors:***

• Focus on consistent quality over aggressive pricing strategies.

• High review volume often accompanies strong ratings. 

• Both fiction and non-fiction have viable paths to bestseller status.


***For Retailers:*** 

• Monitor review volumes as key engagement metrics. 

• Maintain diverse pricing strategies even among bestsellers. 

• Highlight consistently high-rated titles to build customer trust.



**🔬 Future Research Opportunities**


• Compare bestsellers against average-performing books to identify true success predictors

• Analyze post-2020 trends to understand pandemic and digital shift impacts

• Investigate sub-genre patterns within fiction and non-fiction categories

• Track author trajectories and repeat bestseller patterns

• Perform sentiment analysis on review text for deeper quality 

• Examine seasonal patterns in bestseller characteristics



**📝 Skills Demonstrated**


• Data loading and cleaning 

• Exploratory data analysis 

• Statistical analysis and hypothesis testing 

• Data visualization and storytelling 

• Time series analysis 

• Comparative analytics 

• Predictive modeling 

• Critical interpretation of results 

• Business communication



**📧 Questions or Contributions**


Feel free to open an issue or submit a pull request with suggestions, improvements, or additional analysis ideas.



Analysis completed: October 2025

Dataset: Amazon Top 50 Bestsellers (2009-2019)
Tools: Python, Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy

