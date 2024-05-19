# Ecommerce-Product-Categorization
## Introduction

This project aims to categorize ecommerce products based on their descriptions. Proper categorization enhances user experience and improves search engine results. The project involves exploratory data analysis (EDA), text normalization, text vectorization, model training, hyperparameter tuning, evaluation, and the development of a Streamlit web application for product category classification.
## Problem Statement: 

In the rapidly evolving world of eCommerce, accurate product categorization is crucial for ensuring seamless customer experiences, reducing search friction, and increasing product discoverability. However, the sheer volume of diverse products poses a significant challenge. Current classification systems struggle to handle ambiguities, unconventional naming conventions, and multi-language data. This hackathon aims to address these challenges by inviting participants to create innovative solutions that enhance product categorization efficiency, accuracy, and scalability.
Develop a text classification model that categorizes products with maximum accuracy based on description of the product.
## Product Categories

- Automotive
- Baby Care
- Bags, Wallets & Belts
- Clothing
- Computers
- Footwear
- Home Decor & Festive Needs
- Jewellery
- Kitchen & Dining
- Mobiles & Accessories
- Pens & Stationery
- Tools & Hardware
- Toys & School Supplies
- Watche

## Steps Involved

1. **Exploratory Data Analysis (EDA):**
   - An in-depth analysis of the dataset was conducted to understand its structure and characteristics. Visualizations were created to identify trends, distributions, and patterns within the data.

2. **Text Normalization:**
   - Text normalization techniques were applied to both the training and test data. Techniques included:
     - Converting text to lowercase
     - Removing whitespace, punctuation,emojis and special characters
     - Lemmatization
     - Removing stopwords
     - Handling HTML tags and hyperlinks
     - POS Tagging
   - The `text_normalizer` function was used to preprocess the text data.

3. **Text Vectorization:**
   - Text data was vectorized using TF-IDF vectorization.
   - Both the training and test data were transformed into TF-IDF matrix representations.

4. **Model Training:**
   - Nine machine learning models were trained to classify products into predefined categories. The `RidgeClassifier` performed particularly well.

5. **Hyperparameter Tuning:**
   - Hyperparameters of the best performing model were fine-tuned to optimize performance.

6. **Evaluation:**
   - The trained model was evaluated on unseen data to assess its performance. An accuracy of `85%` was achieved.

7. **Streamlit Web Application:**
   - A Streamlit web application was developed to allow users to input product descriptions and classify them into relevant categories.
