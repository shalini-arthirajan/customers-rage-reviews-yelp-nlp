# Customers Rage: Yelp Reviews NLP

1. Applies a pretrained RoBERTa transformer to estimate sentiment (negative/neutral/positive) for Yelp reviews
2. Validates model predictions against user star ratings
3. Analyzes low-rated reviews to identify common factors behind customer dissatisfaction
4. Uses stopword filtering to make real complaints stand out
5. Generates a plot on the model's predictions against star ratings & a chart on the most frequently mentioned terms in complaints

## Issues Faced
1. Keyword frequency is sensitive to common filler words
2. Negation (ex:"not good") can mislead simple word counts
