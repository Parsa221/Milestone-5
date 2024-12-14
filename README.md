# Sentiment Analysis of Financial Terminology in Literature

## General Information
This project examines the evolution of financial terminology in English literature by analyzing *Great Expectations* by Charles Dickens (19th century) and *The Great Gatsby* by F. Scott Fitzgerald (20th century). The study uses Natural Language Processing (NLP) techniques to extract the most frequently used financial terms in these texts and applies sentiment analysis (via Hugging Face models) to evaluate how these terms are contextually framed. The aim is to explore how societal attitudes toward wealth, poverty, and finance differ across these two eras.

## Background Information
Numerous studies have examined the role of language in literature and its reflection of societal values. Two notable studies include:

1. **Jockers, M. L., & Mimno, D. (2013)**: This study explored the thematic structure of 19th-century novels using computational text analysis. Their findings revealed distinct patterns of language use tied to class and economic themes.
2. **Elkins, K. (2019)**: This research investigated sentiment analysis in Victorian literature, highlighting how language reflected societal attitudes toward wealth and morality.

By building on these works, this project focuses on the sentiment and frequency of financial terminology across literary periods.

## Research Question and Hypotheses
### Research Question
How do the 20 most frequently occurring financial terms differ in sentiment across *Great Expectations* by Charles Dickens and *The Great Gatsby* by F. Scott Fitzgerald, and what does this reveal about societal attitudes toward wealth and finance in the 19th and 20th centuries?

### Hypotheses
1. Financial terms in *Great Expectations* will predominantly exhibit negative or moralistic sentiment, reflecting the 19th-century focus on poverty, debt, and social mobility.
2. Financial terms in *The Great Gatsby* will display a mix of positive and neutral sentiment, emphasizing materialism, ambition, and the allure of wealth typical of the Jazz Age.

## Method
### Dataset
- **Texts Used**:
  - *Great Expectations* by Charles Dickens (Project Gutenberg: [Link](https://www.gutenberg.org/ebooks/1400))
  - *The Great Gatsby* by F. Scott Fitzgerald (Project Gutenberg: [Link](https://www.gutenberg.org/ebooks/64317))
  
### Preprocessing
1. Download and clean the texts by removing metadata (e.g., Project Gutenberg headers/footers).
2. Tokenize the text into words and sentences.
3. Normalize the text (e.g., lowercase conversion, lemmatization).

### Sampling Method
1. **Financial Terms Extraction**:
   - Identify the 20 most frequent financial terms in each book using word frequency analysis.
2. **Context Extraction**:
   - Extract all sentences containing these financial terms for sentiment analysis.

### Sentiment Analysis
- Use Hugging Face's pre-trained sentiment analysis model (`distilbert-base-uncased-finetuned-sst-2-english`) to classify sentences as positive, negative, or neutral.

### Analysis Plan
1. Compute the sentiment distribution (positive, negative, neutral) for each term in both books.
2. Compare the sentiment scores across the two books to identify differences in framing.

## Expected Outcomes
This project aims to uncover:
1. The thematic and emotional framing of financial terminology in each literary era.
2. Differences in societal attitudes toward wealth, poverty, and finance between the 19th and 20th centuries.

## Tools and Libraries
- Python (NLTK, Hugging Face Transformers, Matplotlib)
- Jupyter Notebook for analysis
- GitHub for version control and documentation

## References
1. Jockers, M. L., & Mimno, D. (2013). *Significant themes in 19th-century novels: A computational approach*. Digital Scholarship in the Humanities.
2. Elkins, K. (2019). *Sentiment analysis of Victorian novels: Tracing attitudes toward wealth and morality*. Literary and Linguistic Computing.
