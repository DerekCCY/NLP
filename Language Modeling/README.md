# Language Modeling

This project trains an N-gram model and RNN for analyzing song attribution and lyrics generation. 

## Goal
1. **Song attribution:** Train the **Ngram model** on the different singers' lyric datasets and test it with the test dataset. Calculating the perplexity of them to predict that the lyric is most likely to which singers' albums.

2. **Test generation:**  Train an RNN LM using `data/ed_sheeran.txt`. In this part, we use `predict_next_words()` method to generate sentences after the provided phrases from `s1` to `s3`. Use modes `max` and `multinomial`.

3. **Comparison:** **Ngram model**, **RNN**, and **GPT-2**. Train them based on the `data/bbc/tech-small.txt` dataset. Calculating the perplexity of models.

## Experiment
- Run the HW2.ipynb

## Data
- In `data`  

## Model
- Ngram model
- RNN model
- GPT-2 model

## Evaluation
- Perplexity 

## Report: The discussion of this task is in Report.pdf.
