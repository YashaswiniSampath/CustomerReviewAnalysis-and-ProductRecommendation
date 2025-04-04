# Customer Review Analysis and Product Recommendation Project

This project implements a comprehensive approach to analyze customer reviews, extract insights, and provide tailored product recommendations based on user preferences. The project employs sentiment analysis, natural language processing (NLP), clustering, and K-Nearest Neighbors (KNN) techniques to achieve accurate and efficient results.

## Project Overview

The project consists of several components:

1. **Review Mining and Sentiment Analysis:** Extract customer reviews and perform sentiment analysis to classify sentiments as positive, negative, or neutral.

2. **NLP with SpaCy and Hugging Face Transformers:** Leverage SpaCy and Hugging Face Transformers for text analysis and processing tasks.

3. **Statistical Approaches and LDA:** Implement statistical methods and Latent Dirichlet Allocation (LDA) for uncovering latent topics within the review corpus.

4. **3-Layer Matrix Approach:** Hierarchical approach to user-product relationships, considering categories, sub-categories, and unique items.

5. **KNN and Clustering:** Utilize KNN with cosine similarity and clustering algorithms to find user-product relationships.

6. **Handling Large Customer Base:** Use of clusters to represent similar customers, reducing time complexity.

7. **Handling Large Product Catalog:** Categorize products into limited categories and sub-categories.

8. **Handling New Customer Data:** Provide recommendations using best-seller products and user interactions like searches and views.

## Getting Started

1. Clone this repository.
2. Install the required dependencies.
3. Prepare your customer reviews dataset and ensure it's in an appropriate format.
4. Configure the project parameters such as K value for KNN, clustering settings, etc.
5. Run the scripts sequentially, starting from data preprocessing, sentiment analysis, and proceeding to KNN and clustering stages.
6. Analyze the generated insights and recommendations.


## License

This project is licensed under the [MIT License](LICENSE).
dataset:
https://www.kaggle.com/datasets/atharvjairath/flipkart-ecommerce-dataset
---

**Note:** This README provides a high-level overview. Please refer to the scripts and comments within the code for detailed implementation and usage instructions.
