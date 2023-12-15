# Bitcoin Sentiment Analysis on Social Media

## Introduction
This project explores the intriguing connection between social media sentiment, particularly on Twitter, and the price fluctuations of Bitcoin. Leveraging a comprehensive dataset of approximately 91 million tweets, the aim is to uncover how public perception mirrored in social media can influence or reflect the volatile nature of cryptocurrency markets.

## Data Source
The primary dataset for this analysis comes from a Kaggle dataset: [Bitcoin Tweets](https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets), which contains around 91 million tweets.

## Challenges Addressed
Due to the sheer volume and variety of tweets, challenges like unrelated content and potential scams were prevalent. A rigorous data cleaning process was followed by K-means clustering to group similar tweets effectively, enhancing the focus on relevant content.

## Methodology
1. **Data Cleaning:** Preprocessing steps to ensure data quality and relevancy.
2. **K-means Clustering:** Grouping tweets into clusters for easier thematic analysis.
3. **Wordcloud Visualization:** Identifying key themes within each cluster.
4. **Discarding Irrelevant Data:** Filtering out non-relevant or scam-related clusters.
5. **Web-Scraping:** Extracting Bitcoin price history for the month of December 2022 from relevant financial websites.
6. **Exploratory Data Analysis (EDA):** Conducting an initial investigation on the data to discover patterns, spot anomalies, test hypotheses, and check assumptions.

## Sentiment Analysis
Focusing on a sample cluster and the month of December 2022, a sentiment analysis was performed. The overall sentiment related to Bitcoin was found to be mostly positive ("bullish") during this period.

## Data Visualization
Visual tools like WordClouds and sentiment analysis plots were used to effectively communicate the findings and trends observed in the data.

## Comparison with Bitcoin Price Data
The Bitcoin price history for December 2022 was web-scraped and compared with the social media sentiment established for the same period. The analysis revealed a negative correlation between social media sentiment and the actual price of Bitcoin.

## Conclusion
The study demonstrates the potential of combining data analysis and domain knowledge to understand the impact of social media on financial markets, particularly highlighting a negative correlation between social media sentiment and Bitcoin prices.

## Technologies and Libraries Used
- Python
- Jupyter Notebook
- Libraries: numpy, pandas, nltk, sklearn, matplotlib, wordcloud, vaderSentiment, seaborn, BeautifulSoup, requests

## Usage
Follow the Jupyter notebook to replicate the analysis. Ensure to install the necessary Python libraries listed above.

## Acknowledgments
Special thanks to the providers of the Kaggle dataset for enabling this analysis.

## License
[MIT License](LICENSE.md) - feel free to use and modify as per the license terms.

## Contact Information
For further inquiries or collaboration, feel free to reach out on GitHub:  [ https://github.com/Abelenva/ ]
