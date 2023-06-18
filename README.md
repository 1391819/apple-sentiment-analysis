<div align="center">
  <img src="imgs/logo-light-nobg.png" alt="logo" width="128"/>
  <h1>Sentimental Analysis - Apple's reviews</h1>

</div>

<div align="justify">

This project aims to perform sentiment analysis on Apple's reviews gathered from Trustpilot using various Python libraries such as Requests, BeautifulSoup, NLTK, and TextBlob. By extracting review content, ratings, and other relevant information from the web page, this analysis provides insights into the sentiment expressed by customers towards Apple's products and services.

## Roadmap

- [x] Web scrape Apple's reviews from Trustpilot
- [x] Perform data cleaning
- [x] Create additional features (word_count, char_count, average_word_length, stopword_count, stopword_rate)
- [x] Pre-process text data (to lowercase, remove punctuation, stop words, recursive words, extra custom stop words, and lemmatization)
- [x] Perform sentiment analysis
- [x] Evaluate performance and accuracy
- [x] Analyse sentiment scores (polarity and subjectivity)
- [x] Draw conclusions

## Stack

- Requests
- BeautifulSoup
- NLTK
- TextBlob
- Data Cleaning and Interpretation

## Methodology

The methodology consists of several key steps, including web scraping, data cleaning, and sentiment analysis using NLTK and TextBlob.

### Web Scraping

The first step involved web scraping the reviews from Apple's Trustpilot page. The BeautifulSoup library was used to extract the review content, ratings, and other relevant information from the HTML structure of the webpage. The Requests library facilitated the retrieval of the web page's HTML content for further processing.

### Data Cleaning and Feature Creation
Once the reviews were collected, a comprehensive data cleaning process was applied to ensure the quality and reliability of the dataset. Additional features were also created from the reviews to provide more context and enable a more in-depth data analysis (word_count, char_count, average_word_length, stopword_count, stopword_rate).

### Sentiment Analysis
The core objective of this project was to perform sentiment analysis on Apple's reviews. The NLTK library was utilised for tasks such as stop word removal to preprocess the text data. TextBlob, a natural language processing library, was employed to lemmatize the reviews and assign sentiment scores, indicating whether each review expressed a positive, negative, or neutral sentiment. The sentiment analysis results were used to gain insights into the overall sentiment of the reviews and to identify any sentiments associated with specific aspects of Apple's products or services.

## Evaluation and Conclusion

To evaluate the results we used TextBlob's sentiment analysis capabilities to assess the polarity and subjectivity of Apple's reviews. The polarity score indicates the overall sentiment expressed in the reviews, ranging from -1 to 1, where -1 indicates negative sentiment, 0 indicates neutral sentiment, and 1 indicates positive sentiment. On the other hand, the subjectivity score measures the degree of subjectiveness in the reviews, ranging from 0 to 1, where 0 indicates an objective statement, and 1 indicates a subjective statement. 

The analysis revealed that the average polarity score of Apple's reviews was -0.002497, indicating a slightly negative sentiment overall. This suggests that there were more negative or neutral opinions expressed compared to positive ones. However, it is important to note that the magnitude of the polarity score is quite small, suggesting a relatively balanced sentiment.

Furthermore, the average subjectivity score was found to be 0.480238, indicating a moderate level of subjectivity in the reviews. This suggests that while some reviews were objective and based on factual information, a significant portion of the reviews contained subjective opinions or personal experiences.

In conclusion, this project successfully performed sentiment analysis on Apple's reviews gathered from Trustpilot. The analysis revealed a slightly negative sentiment overall, indicating that there were more negative or neutral opinions expressed compared to positive ones. However, the magnitude of the negativity was relatively small, suggesting a balanced sentiment.

Additionally, the reviews exhibited a moderate level of subjectivity, indicating a mix of objective and subjective opinions. This highlights the diverse nature of the feedback provided by customers, with some reviews being based on factual information and others reflecting personal experiences and subjective viewpoints.

The findings from this project can be valuable for Apple to gain insights into customer sentiment, identify areas of improvement, and address customer concerns. By understanding the sentiment and subjectivity of customer reviews, Apple can make data-driven decisions to enhance its products and services, improve customer satisfaction, and maintain a positive brand reputation.

## License

[MIT](https://github.com/1391819/apple-sentiment-analysis/blob/main/License.txt) © [Roberto Nacu](https://github.com/1391819)
