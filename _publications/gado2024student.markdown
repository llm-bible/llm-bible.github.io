---
layout: publication
title: Student Answer Forecasting: Transformer-driven Answer Choice Prediction For Language Learning
authors: Gado Elena Grazia, Martorella Tommaso, Zunino Luca, Mejia-domenzain Paola, Swamy Vinitra, Frej Jibril, Käser Tanja
conference: "Arxiv"
year: 2024
bibkey: gado2024student
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20079"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Intelligent Tutoring Systems (ITS) enhance personalized learning by predicting student answers to provide immediate and customized instruction. However recent research has primarily focused on the correctness of the answer rather than the students performance on specific answer choices limiting insights into students thought processes and potential misconceptions. To address this gap we present MCQStudentBert an answer forecasting model that leverages the capabilities of Large Language Models (LLMs) to integrate contextual understanding of students answering history along with the text of the questions and answers. By predicting the specific answer choices students are likely to make practitioners can easily extend the model to new answer choices or remove answer choices for the same multiple-choice question (MCQ) without retraining the model. In particular we compare MLP LSTM BERT and Mistral 7B architectures to generate embeddings from students past interactions which are then incorporated into a finetuned BERTs answer-forecasting mechanism. We apply our pipeline to a dataset of language learning MCQ gathered from an ITS with over 10000 students to explore the predictive accuracy of MCQStudentBert which incorporates student interaction patterns in comparison to correct answer prediction and traditional mastery-learning feature-based approaches. This work opens the door to more personalized content modularization and granular support.
