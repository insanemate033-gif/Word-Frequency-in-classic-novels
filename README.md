# Word-Frequency-in-classic-novels
## Introduction

This project demonstrates how to analyze the most frequent words in Herman Melville's novel, Moby Dick, and how often they occur. The analysis involves web scraping, text extraction, and natural language processing (NLP) techniques. The pipeline we build in this notebook can be used to visualize word frequency distributions of any novel available on Project Gutenberg.

## Project Workflow

### Scraping the Novel:
We fetch the novel Moby Dick from Project Gutenberg using the Python requests package.

### Extracting Words from HTML:
We use BeautifulSoup to extract the text from the HTML content of the novel.

### Text Processing with NLTK:
Tokenizing the text to extract words.
Cleaning and normalizing the text by removing punctuation, stop words, and converting words to lowercase.
Analyzing word frequency distributions.
