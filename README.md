# A-KEY-DRIVER-ANALYSIS-OF-IMDB-MOVIE-REVIEWS-USING-NLP
## Overview
This project utilizes Natural Language Processing (NLP) to analyze customer feedback and identify key factors influencing satisfaction. By examining the IMDB Movie Reviews Dataset, we aim to uncover actionable insights that can enhance customer experiences.

## Methodology

### Data Acquisition
- **Dataset**: IMDB Movie Reviews Dataset (`IMDBDataset.csv`)
- **Reviews**: 50,000 reviews with corresponding sentiment labels

### Text Preprocessing
- **Cleaning**: Removed HTML tags, non-alphanumeric characters, and converted text to lowercase
- **Tokenization**: Split text into individual words
- **Stop Words Removal**: Removed common words that do not add significant meaning
- **Lemmatization**: Converted words to their base forms

### NLP Techniques
1. **Keyword Extraction**:
   - Identified fifty crucial keywords (single words and bigrams) using TF-IDF vectorization
2. **Sentiment Analysis**:
   - Used TextBlob to determine the sentiment polarity (positive, negative, neutral) for each keyword
3. **Importance Ranking**:
   - Calculated keyword importance by multiplying its frequency with the absolute sentiment score
   - Ranked keywords based on importance (highest to lowest)
4. **Visualization**:
   - Created a scatter plot to visualize the relationship between keyword frequency (Y-axis) and sentiment polarity (X-axis)
   - Point size and color represent the relative importance of each keyword

## Findings
1. **Character Focus & Pacing**:
   - Characters (development or memorability) and pacing (mentions of "time") are key factors in viewer perception, indicating potentially engaging movies.
2. **Positive Reception**:
   - Most keywords have positive sentiment (e.g., "great," "well," "good"), suggesting viewers enjoyed the films.
3. **Frequent Mentions**:
   - High-frequency terms (e.g., "good," "see") showcase viewer interest.

## Actionable Insights
1. **Unpopular Characters**:
   - Address negative sentiment around characters by refining motivations/actions to improve likability.
2. **Pacing Issues**:
   - Address negative "time" mentions by tightening the script. Remove unnecessary scenes and ensure smooth story flow.
3. **Fan Favorites**:
   - Leverage frequently mentioned positive aspects in future projects, such as character types, plot elements, or thematic focus.

## Conclusion
Based on the analysis of IMDb movie reviews, enhancing viewer engagement hinges on character development and pacing. Positive sentiment regarding characters and frequent mentions of enjoyable aspects indicate a need to refine character motivations and streamline script pacing. Leveraging popular elements can optimize film appeal, ensuring enhanced viewer satisfaction and success.




