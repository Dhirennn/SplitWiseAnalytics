# SplitWise Analytics

This repository contains the code and datasets used for analyzing SplitWise user reviews and identifying key reasons for its success. The project focuses on understanding user sentiment, feature usage, and pain points using data scraped from the Google Play Store.

## Quick View of Splitwise Analytics
To just view the visualizations, you can open up the `Dhiren_SplitWise_Analytics.pdf` PDF.

### Example View
![Image not available :(](https://ibb.co/Wzv5ksx)

Note: `splitwise_reviews.csv` was scraped using the `Crawl_Data.ipynb` scraper.

## Repository Structure

### Folders and Files:

1. **`Crawl_Dataset/`**
   - Directory to store all the scraped review data from the Google Play Store.

2. **`Crawl_Data.ipynb`**
   - Jupyter Notebook used for scraping SplitWise user reviews from the Google Play Store.
   - Contains code for web crawling, parsing reviews, and exporting data into a CSV format.

3. **`splitwise_reviews.csv`**
   - The dataset containing the scraped user reviews.
   - Includes fields such as review ID, username, review content, score, and app version.

4. **`SplitWise_Analytics.ipynb`**
   - Jupyter Notebook for performing data analysis on the scraped reviews.
   - Includes:
     - Data cleaning and preprocessing.
     - Sentiment analysis of reviews.
     - N-gram analysis to identify common phrases (e.g., bigrams and trigrams).
     - Visualizations to highlight user feedback trends.

5. **`README.md`**
   - This file, providing an overview of the repository and instructions for usage.

## Project Highlights

### Objective:
To analyze SplitWise user reviews to uncover:
- Key reasons for its success.
- Features most appreciated by users.
- Common pain points and areas for improvement.

### Features:
- Scraping user reviews from the Google Play Store.
- NLP techniques to extract insights, such as:
  - Most frequent keywords and phrases.
  - Sentiment analysis.
  - Feature-specific user feedback.
- Visualizations to communicate insights effectively.

### Tools and Libraries Used:
- **Python**
- **Pandas**: For data manipulation.
- **NLTK**: For text preprocessing and tokenization.
- **Scikit-learn**: For vectorizing text and extracting n-grams.
- **Matplotlib & Seaborn**: For creating visualizations.
- **google-play-scraper**: For scraping the Google Play Store Reviews.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Dhirennn/SplitWiseAnalytics.git
   cd SplitWise_Analytics
  
2. **Open Jupyter Notebook in your terminal in the same directory as `SplitWise_Analytics.ipynb`:**
   ```bash
   jupyter notebook
  
3. **Open`SplitWise_Analytics.ipynb` and run all cells**

