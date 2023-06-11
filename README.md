<div align="center">
  <img src="imgs/logo-light-nobg.png" alt="logo" width="128"/>
  <h1>Sentimental Analysis - Apple's reviews</h1>

</div>

<div align="justify">

This project aims to perform sentiment analysis on Apple's reviews gathered from Trustpilot using various Python libraries such as Requests, BeautifulSoup, NLTK, and TextBlob. By extracting review content, ratings, and other relevant information from the web page, this analysis provides insights into the sentiment expressed by customers towards Apple's products and services.

## Features
- Web scraping of business reviews from Apple's TrustPilot page
- Data cleaning and preprocessing for quality and reliability
- Creation of additional features for a more comprehensive analysis
- Sentiment analysis using NLTK and TextBlob to determine positive, negative, or neutral sentiment

## Stack

- Requests
- BeautifulSoup
- NLTK
- TextBlob
- Data Cleaning and Interpretation

## Data Overview

- Web scraped business reviews from Apple's TrustPilot page
- Additional - manually created - features from reviews for a more in-depth data analysis

## Methodology

The methodology consists of several key steps, including web scraping, data cleaning, and sentiment analysis using NLTK and TextBlob.

### Web Scraping

The first step involved web scraping the reviews from Apple's Trustpilot page. The BeautifulSoup library was used to extract the review content, ratings, and other relevant information from the HTML structure of the webpage. The Requests library facilitated the retrieval of the web page's HTML content for further processing.

### Data Cleaning and Feature Creation
Once the reviews were collected, a comprehensive data cleaning process was applied to ensure the quality and reliability of the dataset. This involved tasks such as handling missing values, removing duplicates, and standardizing the text format. Additional features were created from the reviews to provide more context and enable a more in-depth data analysis (i.e., length of the reviews, presence of specific keywords, sentiment scores obtained from TextBlob).

### Sentiment Analysis
The core objective of this project was to perform sentiment analysis on Apple's reviews. The NLTK library was utilized for tasks such as tokenization, stop word removal, and stemming to preprocess the text data. TextBlob, a natural language processing library, was employed to assign sentiment scores to the reviews, indicating whether each review expressed a positive, negative, or neutral sentiment. The sentiment analysis results were used to gain insights into the overall sentiment of the reviews and to identify any sentiments associated with specific aspects of Apple's products or services.

## Evaluation and Conclusion

...

## License

[MIT](https://github.com/1391819/apple-sentiment-analysis/blob/main/License.txt) © [Roberto Nacu](https://github.com/1391819)
