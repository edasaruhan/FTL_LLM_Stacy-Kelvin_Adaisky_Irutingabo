# Sentiment Analysis of Product Reviews

## Project Overview

This project focuses on developing a sentiment analysis model to classify product reviews into positive, neutral, or negative sentiments. The goal is to help businesses understand customer feedback and improve their product offerings.

## SDG Goal

**SDG 8 - Decent Work and Economic Growth**

## Objective

To develop a sentiment analysis model using the BERT architecture to classify product reviews from the Amazon Product Reviews dataset into three categories: positive, neutral, or negative.

## Dataset

The dataset used for this project is the **Amazon Product Reviews dataset**, which contains millions of product reviews categorized by sentiment. 

- **Source**: [Link to dataset] (if available)
- **Format**: CSV
- **Columns**: 
  - `Text`: Review text
  - `Score`: Rating score
  - `sentiment`: Label (0 for Negative, 1 for Neutral, 2 for Positive)

## Metrics

The model evaluation includes the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score

## Example

### Training Output

```plaintext
Evaluation results: {'eval_loss': 0.435861736536026, 'eval_accuracy': 0.885, 'eval_f1': 0.8713770106845133, 'eval_precision': 0.8624061085972852, 'eval_recall': 0.885, 'eval_runtime': 248.226, 'eval_samples_per_second': 0.806, 'eval_steps_per_second': 0.052, 'epoch': 3.0}


### Testing Example

```plaintext
Text: My son loved the original recipe Chick Chick but Happy Baby has now changed the recipe.  My son retched upon the first bite of the new meal.  Why do companies try to improve upon something that already works.  I'm guessing to cut corners somehow (ie. cheaper ingredients).  It's a shame.  I now have a case of the new recipe that won't be eaten.
Predicted Sentiment: Negative

Text: Nothing amazing about this little blade.  Used to make Zuchinni Noodles.  Worked Perfectly.<br />No Problems yet.<br />Kind of wish I had gone with one of those multi blade peelers but this was a little cheeper, and I ofern find multi use items tend to break often.
Predicted Sentiment: Positive

Text: My 10 month old baby hates this stuff!!  I've tried giving it to him on 4 separate occasions-but everytime he tastes it--he makes a disgusted look and won't eat anymore.  I even tried mixing it with his favorite foods and he just takes one bite and looses his appetite and won't eat anymore of anything for the rest of the night!
Predicted Sentiment: Negative

```
