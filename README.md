### yelp-scrape-review-sentiment
Text Mining | Web Scraping | Yelp API | Sentiment Analysis

Scraping text data and ratings from restaurant reviews on Yelp to build a Sentiment Analysis Model.
## Yelp Review Sentiment Analysis
This project uses Yelp's API to scrape customer reviews and ratings for restaurants in Toronto. It then uses Natural Language Processing (NLP) techniques to analyze the sentiment of the reviews.

The project is implemented in Python and uses the following libraries:

-requests
-BeautifulSoup
-nltk
-matplotlib

### The project is structured into the following sections:

1. API Request: A GET request is sent to the Yelp API to retrieve a list of restaurants in Toronto. The response is parsed to extract the URLs of the restaurants.

2. Review URLs: For each restaurant, the code retrieves the URLs of all its reviews. It also determines the number of pages of reviews for each restaurant.

3. Scraping Reviews: The URLs of the reviews are used to scrape the reviews and ratings for each restaurant. The reviews and ratings are stored in two separate lists.

4. Sentiment Analysis: The reviews are pre-processed and feature extraction is performed using nltk. The features are then used to train a Naive Bayes classifier to predict the sentiment of the reviews.

5. Visualization: The sentiment analysis results are visualized using a bar graph.
