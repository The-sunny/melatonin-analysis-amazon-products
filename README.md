# Amazon Melatonin Review Analysis

- **Python, Pandas, Matplotlib, Seaborn, NLP, Sentiment Analysis**
- Data scraped from **Amazon & Walmart**
- Analyze **melatonin product doses, forms, brands, and user reviews**
- Combine **EDA + NLP** for insights on dosage distribution, product features, and consumer sentiment

> This project explores the chaotic market of melatonin supplements. With doses ranging from **1mg to 25mg** across different brands, forms (gummies, tablets), and flavors, the project combines **exploratory data analysis** with **natural language processing** to understand user experience, product effectiveness, and overall market response.

---

## Data Background

The dataset was scraped from Amazon and Walmart

Includes details on brands, doses, forms (gummies/tablets), flavors, ratings, and reviews

Objective: Explore how dosage levels affect ratings, sentiment, and user experiences

## Analysis Workflow
🔹 Exploratory Data Analysis (EDA)

- Distribution of brands, doses, forms, flavors

- Ratings vs. different doses

- Univariate, bivariate, multivariate visualizations

🔹 Natural Language Processing (NLP)

- Data cleaning (stopwords, punctuation, stemming, lemmatization)

- Word frequency and n-grams (2-grams, 3-grams)

- Word clouds of common phrases in reviews

- Sentiment analysis (positive, neutral, negative, polarity, subjectivity)

- Sentiment trend across different doses and over time

- Hot word extraction (e.g., "fall asleep in 30 minutes")

## Key Insights

- Which dosages (1mg, 3mg, 5mg, 10mg, 20mg, etc.) are most common

- Which forms (gummies vs tablets) are most preferred

- Which flavors are popular (strawberry, citrus, etc.)

- How long after taking melatonin people feel sleepy

- User sentiment across doses and trends over time

- Which doses people recommend most frequently

## Future Enhancements

- Deploy an interactive dashboard (Plotly/Dash or Streamlit)

- Build a recommendation system for melatonin products

- Perform topic modeling (LDA) to discover hidden themes in reviews

- Extend analysis to other supplements for broader market insights
