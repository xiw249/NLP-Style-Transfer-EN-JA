# Sentiment-Neutral Style Transfer in English-to-Japanese Machine Translation
> An academic research project investigating a novel approach to remove sentiment during machine translation using a reinforcement learning framework.

## Project Goal

Traditional methods for text style transfer often rely on back-translation to create a style-neutral latent representation of a sentence. This project proposed a more direct and innovative approach: fine-tuning an English-to-Japanese translation model to **purge sentiment (a form of style) in a single translation step**.

The goal was to create a style-agnostic latent representation in the target language (Japanese) by optimizing the model with a custom reward function that encourages semantic preservation while maximizing sentiment ambiguity.

## My Specific Contributions

In this research-focused group project, my role centered on data management and providing essential linguistic expertise:

- **Data Curation & Processing:** I was responsible for sourcing, curating, and processing the key datasets for this project. This included the **English Yelp dataset** (as a source of sentiment-rich text) and the **Japanese CHABSA dataset** (intended for the style re-application phase).
- **Japanese Linguistic Expertise:** I provided critical Japanese language support to the team. This involved evaluating the quality, coherence, and nuances of machine-generated translations, which was essential for tackling the significant linguistic challenges between English and Japanese.
- **Project Collaboration:** I participated in project planning, literature review, and the analysis of the baseline back-translation model's performance.

## Methodology & Tech Stack

Our proposed method involved fine-tuning a pre-trained **Helsinki-NLP** English-to-Japanese model. The fine-tuning was designed as a **Reinforcement Learning** task, where the reward function was based on the output of a **BERT-based Japanese sentiment classifier**.

- **Languages:** Python
- **Frameworks & Models:** Hugging Face Transformers, BERT, Helsinki-NLP Models
- **Conceptual Framework:** Reinforcement Learning (RL)

## Outcomes & Full Report

While the RL training phase presented significant challenges (as detailed in the report), this project provided deep insights into the complexities of cross-lingual style transfer and fine-grained control of text generation.

For a complete description of our proposed methodology, experimental setup, and detailed analysis, please see the full final report.

**[View Full Report (PDF)](./Report.pdf)**

## Team

This project was a collaborative research effort with my teammates: [Annanya, Jayden Serenari, Noah Bright].
