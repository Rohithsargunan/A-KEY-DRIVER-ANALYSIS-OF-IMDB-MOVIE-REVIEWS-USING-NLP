# A-KEY-DRIVER-ANALYSIS-OF-IMDB-MOVIE-REVIEWS-USING-NLP
Introduction
This report utilizes Natural Language Processing (NLP) to dissect customer feedback and pinpoint key factors influencing satisfaction. By analyzing the IMDB Movie Reviews Dataset, we aim to identify actionable insights that can be applied to enhance customer experiences.

Methodology
Data Acquisition
The IMDB Movie Reviews Dataset (IMDBDataset.csv) containing 50,000 reviews and corresponding sentiment labels was used as the data source.
Text Preprocessing
Reviews underwent cleaning to remove HTML tags, non-alphanumeric characters, and were converted to lowercase.
Text was tokenized, with stop words removed and words lemmatized.
NLP Techniques
Keyword Extraction: Fifty crucial keywords (single words and bigrams) were identified using TF-IDF vectorization.
Sentiment Analysis: TextBlob was employed to determine the sentiment polarity (positive, negative, neutral) for each keyword.
Importance Ranking: Keyword importance was calculated by multiplying its frequency with the absolute sentiment score. Keywords were then ranked based on this score (highest to lowest importance).
Visualization: A scatter plot was created to visualize the relationship between keyword frequency (Y-axis) and sentiment polarity (X-axis). Point size and color represent the relative importance of each keyword.
Findings
Character Focus & Pacing: Analysis suggests characters (development or memorability) and pacing ("time" mentions) are key factors in viewer perception, indicating a potentially engaging movie.
Positive Reception: Most keywords have positive sentiment ("great," "well," "good"), suggesting viewers enjoyed the film.
Frequent Mentions: High-frequency terms ("good," "see") showcase viewer interest.
Actionable Insights
Unpopular Characters: Negative sentiment around characters suggests script revisions. Refine motivations/actions to improve likability.
Pacing Issues: Address negative "time" mentions by tightening the script. Remove unnecessary scenes and ensure smooth story flow.
Fan Favorites: Leverage frequently mentioned positive aspects in future projects. This can involve character types, plot elements, or thematic focus.
Conclusion
Based on the analysis of IMDb movie reviews, enhancing viewer engagement hinges on character development and pacing. Positive sentiment regarding characters and frequent mentions of enjoyable aspects indicate a need to refine character motivations and streamline script pacing. Leveraging popular elements can optimize film appeal, ensuring enhanced viewer satisfaction and success.
