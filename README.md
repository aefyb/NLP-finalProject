# NLP-finalProject
Final Project for Text Mining &amp; NLP Essentials

This project was done by Alex Ibrahim, Leslie Juarez, Chinonye Mgboji, and Jessica Nguyen

## Goals
The goal of this project was to utilize NLP techniques on customer reviews of a variety of products in order to bridge the gap between the buyer's experience and product development.

We aim to:

- help consumers make informed decisions before purchasing a product
- and provide sellers important data to refine their products

## Dataset
The link to the dataset: https://www.kaggle.com/datasets/niraliivaghani/flipkart-product-customer-reviews-dataset

### Description
The Kaggle dataset contains 205,053 reviews on a variety of Flipkart products, including clothing, electronics, and home decor. The reviews were scraped from Flipkart's website in 2022, and then labeled based on the sentiment of the review's summary.

### Features
The features in our dataset are
- product_name (Name of the product)
- product_price (Price of the product)
- Rate (Rating of the review on a scale of 1-5)
- Review (Customer's review of the product)
- Summary (Customer's thought on each product)
- Sentiment (3 labels: Positive, Neutral, Negative [Based on the summary])

## Reproducibility
Our results can be replicated using Google Colab or through conda in Jupyter Notebook.
### Google Colab
To use the code in Google Colab:
1. Download the `Dataset-SA.csv` dataset file
2. Download the `I_320D_Flipkart_Product_Review_Analysis.ipynb` code file
3. Import the interactive python notebook into Colab
4. Import dataset file into Google Colab's files
5. To ensure no errors, make sure to uncomment the pip installs in code blocks 1 and 30.
6. Run the file.
### Jupyter Notebook
1. Download the `Dataset-SA.csv` dataset file
2. Download the `I_320_Flipkart_Product_Review_Analysis.ipynb` code file
3. Download either `environment.yml` or `library_requirements.txt` in the `environment_files` directory to have the correct environment
4. For either file, use `conda create -n <env_name> -f <file.extension>`
5. Import the dataset and code files into a directory
6. Run the file as is.

## Additional Notes
Our code contains snippets used in _Topic Modeling with Gensim (Python)._

The link to the website: https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/#17howtofindtheoptimalnumberoftopicsforlda

## References
Vaghani, N., & Thummar, M. (2023). Flipkart Product reviews with sentiment Dataset [Data set]. Kaggle. https://www.kaggle.com/datasets/niraliivaghani/flipkart-product-customer-reviews-dataset

Varma, A. (2022, August 26). Topic Modeling with Gensim (Python). Machine Learning Plus. https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/#17howtofindtheoptimalnumberoftopicsforlda 
