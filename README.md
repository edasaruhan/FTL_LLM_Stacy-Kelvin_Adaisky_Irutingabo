# 1.Sentiment Analysis of Product Reviews

## Project Overview

This project focuses on developing a sentiment analysis model to classify product reviews into positive, neutral, or negative sentiments. The goal is to help businesses understand customer feedback and improve their product offerings.

## SDG Goal

**SDG 8 - Decent Work and Economic Growth**

## Objective

To develop a sentiment analysis model using the BERT architecture to classify product reviews from the Amazon Product Reviews dataset into three categories: positive, neutral, or negative.

## Dataset

The dataset used for this project is the **Amazon Product Reviews dataset**, which contains millions of product reviews categorized by sentiment. 

- **Source**: Kaggle
- **Format**: CSV
- **Columns**: 
  - `Text`: Review text
  - `Score`: Rating score
  - `sentiment`: Label (0 for Negative, 1 for Neutral, 2 for Positive)

## Metrics

The model evaluation includes the following metrics:
- Accuracy : 0.885
- Precision : 0.8624061085972852
- Recall :  0.885
- F1 Score :  0.8713770106845133

### Testing Example

```plaintext
Text: My son loved the original recipe Chick Chick but Happy Baby has now changed the recipe.  My son retched upon the first bite of the new meal.  Why do companies try to improve upon something that already works.  I'm guessing to cut corners somehow (ie. cheaper ingredients).  It's a shame.  I now have a case of the new recipe that won't be eaten.
Predicted Sentiment: Negative

Text: Nothing amazing about this little blade.  Used to make Zuchinni Noodles.  Worked Perfectly.<br />No Problems yet.<br />Kind of wish I had gone with one of those multi blade peelers but this was a little cheeper, and I ofern find multi use items tend to break often.
Predicted Sentiment: Positive

Text: My 10 month old baby hates this stuff!!  I've tried giving it to him on 4 separate occasions-but everytime he tastes it--he makes a disgusted look and won't eat anymore.  I even tried mixing it with his favorite foods and he just takes one bite and looses his appetite and won't eat anymore of anything for the rest of the night!
Predicted Sentiment: Negative

```






# 2.Python-Only Question Answering Model

## Project Overview
This project focuses on creating a model that exclusively answers Python-related questions. If a question is unrelated to Python, the model responds with "I don't know the answer."

## SDG Goal
SDG 4 - Quality Education

## Objective
To develop a text classification model that filters and answers Python-related questions while rejecting non-Python queries.

## Dataset
- **Python-Related Questions**: A collection of Python-related questions sourced from various programming forums.
- **Non-Python-Related Questions**: A collection of general knowledge and non-Python-related queries.


## Model
- **Model Architecture**: A Gpt2-based model fine-tuned to classify questions as Python-related or not.
- **Training**: Trained using a dataset labeled with Python-related and non-Python-related tags.




## Testing Example
- **Query**: "How do I install a package in Python?"
  - **Response**: "How do I install a package in Python? you the in the installed.. command a you ` command, not. and you using of're a you pip your by,,. not on pip.
` install the- Python, Python"
- **Query**: "What is the weather today?"
  - **Response**: "What is the weather today?"

## due to a limit dataset the model is not working well , i had to reduce the dataset because the time of the model to learning was so big





# 4.Text Document Classification

## Overview
This project focuses on classifying and clustering text documents. The dataset contains 2,225 samples categorized into:

- Politics
- Sport
- Tech
- Entertainment
- Business

## Models Used
- **Word2Vec:** Generates word embeddings using a shallow neural network.
- **GloVe:** Creates word embeddings based on global word-word co-occurrence statistics.
- **BERT:** Provides context-aware embeddings using a transformer-based model.
- 
## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook (optional)

Open and run the `.ipynb` files to explore the dataset and models.



This version covers the essentials while keeping it brief. Adjust the contact information and other specifics as needed.
## Contact
Created by [Stacy-Kelvin](https://github.com/yourusername).

---
