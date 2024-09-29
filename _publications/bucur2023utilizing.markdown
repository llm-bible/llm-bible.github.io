---
layout: publication
title: Utilizing Chatgpt Generated Data To Retrieve Depression Symptoms From Social Media
authors: Bucur Ana-maria
conference: "Arxiv"
year: 2023
bibkey: bucur2023utilizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.02313"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
In this work we present the contribution of the BLUE team in the eRisk Lab task on searching for symptoms of depression. The task consists of retrieving and ranking Reddit social media sentences that convey symptoms of depression from the BDI45;II questionnaire. Given that synthetic data provided by LLMs have been proven to be a reliable method for augmenting data and fine45;tuning downstream models we chose to generate synthetic data using ChatGPT for each of the symptoms of the BDI45;II questionnaire. We designed a prompt such that the generated data contains more richness and semantic diversity than the BDI45;II responses for each question and at the same time contains emotional and anecdotal experiences that are specific to the more intimate way of sharing experiences on Reddit. We perform semantic search and rank the sentences relevance to the BDI45;II symptoms by cosine similarity. We used two state45;of45;the45;art transformer45;based models (MentalRoBERTa and a variant of MPNet) for embedding the social media posts the original and generated responses of the BDI45;II. Our results show that using sentence embeddings from a model designed for semantic search outperforms the approach using embeddings from a model pre45;trained on mental health data. Furthermore the generated synthetic data were proved too specific for this task the approach simply relying on the BDI45;II responses had the best performance.
