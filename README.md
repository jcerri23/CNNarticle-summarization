# Text Mining for Abstractive Summarization with T5

## Project Overview

This project explores how text mining techniques can be applied to the task of **abstractive summarization**, specifically across a collection of news articles. The primary goal is to understand and improve the abstractive summarization capabilities of the **T5 model**.

Abstractive summarization goes beyond simply extracting sentences from the source text; it involves comprehending the core meaning and generating a concise, coherent summary that may include rephrased or newly generated content.

## Objectives

- Evaluate the performance and limitations of the pre-trained T5 base model on the summarization task.
- Fine-tune the base model to enhance its ability to generate consistent and meaningful summaries.
- Use two evaluation metrics — **ROUGE** and **BERTScore** — to assess the quality of generated summaries.

## Dataset

The project uses the **CNN/DailyMail dataset (version 2.0.0)**, a widely used English-language dataset comprising over 300,000 news articles written by journalists from CNN and the Daily Mail.

Due to resource constraints, a restricted subset of the dataset is used, containing the first **5,000 articles**.

## Key Insights and Techniques

- Analysis of **Zipf’s Law** applied to word frequency distribution in the dataset.
- Generation of **word clouds** for visualizing prominent terms.
- Exploration of **subword tokenization** techniques utilized by the T5 model.
- **Fine-tuning** the pre-trained T5 model to improve summarization results.
- Evaluation using both **traditional (ROUGE)** and **modern (BERTScore)** metrics to measure summary quality.


