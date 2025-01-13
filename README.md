# Sentiment Analysis of Financial Terms in Literature

## General Information
This project looks at how financial words are used in two famous books: *Great Expectations* by Charles Dickens (19th century) and *The Great Gatsby* by F. Scott Fitzgerald (20th century). I want to see how these words are connected to feelings like positive, negative, or neutral emotions. By doing this, we can learn how people in those times thought about money, wealth, and finance.

## Background Information
Some studies have looked at how language shows feelings and ideas about society:
1. **Jockers and Mimno (2013)**: They studied themes in 19th-century books using computer tools. They found that language often reflected class and money-related issues.
2. **Buechel, S., A. Buffone, B. Slaff, L. Ungar, and J. Sedoc (2018).**: conducted sentiment analysis on historical texts, demonstrating how emotional language reflects social and economic conditions over time.

My project builds on these ideas, focusing on financial words and their emotions in two different time periods.

## Research Question and Hypotheses
### Research Question
How are the 10 most frequent financial words in *Great Expectations* and *The Great Gatsby* connected to emotions, and what does this show about how people thought about money in the 19th and 20th centuries?

### Hypotheses
1. In *Great Expectations*, financial words will mostly have negative emotions, showing worry about poverty, debt, and class struggles.
2. In *The Great Gatsby*, financial words will have a mix of positive and neutral emotions, showing excitement about wealth and the American Dream.

## Method
### Dataset
- **Texts Used**:
  - *Great Expectations* by Charles Dickens (Project Gutenberg: [Link](https://www.gutenberg.org/ebooks/1400))
  - *The Great Gatsby* by F. Scott Fitzgerald (Project Gutenberg: [Link](https://www.gutenberg.org/ebooks/64317))
### Word extraction using Python
1. Write a Python program to:
   - Find the most frequent financial words in both books.
   - Pick 10 most frequent financial term from each book. 
2. Use Hugging Face to check the sentiment (positive, negative, or neutral) of sentences with these words.
3. Compare the results between the two books.

## Expected Outcomes
This study will show:
1. How financial words are emotionally framed in the two books.
2. Differences in how people in the 19th and 20th centuries felt about wealth and money.

## Tools
- Python
- Hugging Face Transformers
- Pycharm
- GitHub

## References
1. Jockers, M. L., & Mimno, D. (2013). *Significant themes in 19th-century novels: A computational approach*. Digital Scholarship in the Humanities.
2. Buechel, S., A. Buffone, B. Slaff, L. Ungar, and J. Sedoc (2018). Modeling empathy and dis-tress in reaction to news stories. arXiv preprint arXiv:1808.10399.
