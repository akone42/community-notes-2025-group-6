### Replicating Birdwatch Figures - Twitter’s Community Notes Analysis

This R Markdown project reproduces key visualizations and analysis from Twitter's Birdwatch (Community Notes) platform, based on publicly available datasets. The figures explore note classifications, trustworthiness, helpfulness ratings, and regression analysis to understand patterns in misinformation labeling and community feedback.

### Figures and Analysis Overview

Figure 2: Classification vs. Trustworthiness
Bar chart showing how notes labeled as “Misleading” or “Not Misleading” differ by presence of trustworthy sources.

Figure 3: Misleading Note Types
Summarizes various types of misinformation (e.g., Factual Error, Manipulated Media).

Figure 4: Not Misleading Note Types
Shows reasons for labeling notes as not misleading (e.g., Factually Correct, Personal Opinion).

Figure 5c: Word Count Distribution (CCDF)
Analyzes word count in summaries across note classifications using Complementary CDF.

Figure 7a: Helpful Ratio by Classification
Displays how helpful users found notes by classification, using ratio and CCDF.

Figure 7b: Total Votes Distribution
Compares how often notes receive votes and how that varies by classification.

Figure 8: Distribution of Helpful Ratings
Breakdown of reasons why a note was marked helpful (e.g., Informative, Empathetic).

Figure 9: Distribution of Unhelpful Ratings
Breakdown of reasons why a note was marked unhelpful (e.g., Incorrect, Off Topic).

Figure 10: Logistic Regression on Helpfulness
Predicts whether a note is helpful based on:

    Misleading classification

    Trustworthy sources

    Summary word count

    Source's follower/friend count, verified status, account age

Extension Question:

For the extension we can check the relationship between nodes classified as notmisleading and helpfulness. That is we can check the pearson r cooleration beetween notes classified as notmisleading and the feautre helpful.