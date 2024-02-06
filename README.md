# Lab Task 3

## Overview
This lab task involves creating a tool to classify emails, implementing an English-Spanish dictionary, and performing various operations on a dataset using pandas.

### Tasks
1. **Classify Emails:**
   - Develop a function `classify_emails` that categorizes emails into "Important," "Promotions," and "Spam" based on keywords and content analysis.
   - Loop through the emails and identify keywords to determine their category.
   - Return three lists of emails for each category.
   - Print the lists.

2. **English-Spanish Dictionary:**
   - Create a basic English-Spanish dictionary allowing users to look up English words and find their Spanish translations.
   - Ask the user to input an English word and print its Spanish translation if available.

3. **Pandas Operations:**
   - Use a dataset containing video game sales data.
   - Calculate total global sales for all games.
   - Find the game with the highest global sales.
   - Determine average sales for each region (NA_Sales, EU_Sales, JP_Sales, Other_Sales).
   - Find the top 5 most popular game genres based on global sales.
   - Calculate total sales for each genre in each region and find the most popular genre in North America.
   - Display the last 10 rows of the dataset.
   - Determine the top 3 gaming platforms with the highest global sales.
   - Calculate the market share (percentage of global sales) for each genre.
   - Calculate the correlation coefficient between NA_Sales and EU_Sales.

4. **NumPy Operations:**
   - Reshape a 1D NumPy array into a 2D array with dimensions (3, 4).
   - Concatenate two NumPy arrays horizontally and vertically.

## Implementation
- For the email classification task, a Python function is developed to categorize emails based on keywords and content analysis. The function loops through the emails and assigns categories based on predefined criteria.
- An English-Spanish dictionary is implemented using Python, allowing users to look up English words and find their Spanish translations. NLTK is used for word tokenization and lemmatization.
- Pandas library is used to perform various operations on a dataset containing video game sales data. Data is loaded into a DataFrame, and operations such as sum, mean, groupby, and correlation are performed to analyze the dataset.
- NumPy library is used for array manipulation and operations. Arrays are reshaped and concatenated horizontally and vertically.

## Dependencies
- Python 
- Pandas
- NumPy

## Usage
1. Run the provided Python scripts for each task.
2. Follow the instructions to interact with the tools or view the results of the operations.

## Author
[Shahzaib Ali]

