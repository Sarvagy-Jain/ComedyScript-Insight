# Stand-Up Comedy Style Analysis

## Project Overview

This project aims to analyze stand-up comedy transcripts to identify similarities and differences in the comedy styles of various comedians. The analysis includes data cleaning, Exploratory Data Analysis (EDA), Sentiment Analysis, Topic Modeling using Latent Dirichlet Allocation (LDA), and Text Generation using Markov chains.

## Data Cleaning

Data cleaning is a crucial yet often tedious task that significantly impacts the quality of analysis.
### Objective:

1. **Getting the Data:**
   - Collect stand-up comedy transcripts from [Scraps From The Loft](https://scrapsfromtheloft.com/).
   - Choose comedians with the highest ratings from [IMDb](https://www.imdb.com/).

2. **Cleaning the Data:**
   - Perform necessary cleaning steps to handle inconsistencies, noise, and irrelevant information.
  

3. **Organizing the Data:**
   - Organize the cleaned data into a structured format.
   - Ensure each comedian's transcripts are saved in separate files or folders.

### Output:

Cleaned and organized data in two standard text formats:

- **Corpus:**
  - A collection of text, ready for analysis.

- **Document-Term Matrix:**
  - Word counts represented in matrix format, facilitating input into other algorithms.

## Features

- **Exploratory Data Analysis (EDA):**
  - Word frequency analysis
  - Amount of Profanity
  - Number of Words
  - 
- **Sentiment Analysis:**
  - Utilizes the TextBlob module to analyze sentiment
  - Provides sentiment labels using polarity and subjectivity

- **Topic Modeling:**
  - Applies Latent Dirichlet Allocation (LDA) for topic modeling
  - Identifies underlying themes in stand-up comedy transcripts

- **Text Generation:**
  - Uses Markov chains for basic text generation
  - Generates text based on the dependency assumption of the previous word.

