AI-Powered Psychological Trait Analysis via Semantic Similarity
Description
This Natural Language Processing (NLP) project uses a sophisticated AI model to measure the "psychological alignment" between a standardized personality questionnaire (Need for Cognition) and a set of free-form personal statements. It goes beyond simple keyword matching to understand the underlying semantic meaning of the text.

Key Features
Semantic Analysis: Utilizes the sentence-transformers library to generate high-dimensional vector embeddings, capturing the contextual meaning of text.

Custom Scoring Engine: Calculates a nuanced psychological alignment score based on the similarity between text embeddings.

Rules-Based Adjustments: Incorporates a system to handle reverse-scored questions and apply keyword weights for improved accuracy.

Data Visualization: Employs a heatmap using Seaborn and Matplotlib to provide an intuitive overview of the results.
