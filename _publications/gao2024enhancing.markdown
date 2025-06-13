---
layout: publication
title: 'Enhancing Emotion Prediction In News Headlines: Insights From Chatgpt And Seq2seq Models For Free-text Generation'
authors: Ge Gao, Jongin Kim, Sejin Paik, Ekaterina Novozhilova, Yi Liu, Sarah T. Bonna, Margrit Betke, Derry Tanti Wijaya
conference: "Proceedings of the 2024 Joint International Conference on Computational Linguistics Language Resources and Evaluation (LREC-COLING 2024) 5944-5955"
year: 2024
bibkey: gao2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.10091'}
tags: ['Language Modeling', 'Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Applications', 'Pretraining Methods']
---
Predicting emotions elicited by news headlines can be challenging as the task
is largely influenced by the varying nature of people's interpretations and
backgrounds. Previous works have explored classifying discrete emotions
directly from news headlines. We provide a different approach to tackling this
problem by utilizing people's explanations of their emotion, written in
free-text, on how they feel after reading a news headline. Using the dataset
BU-NEmo+ (Gao et al., 2022), we found that for emotion classification, the
free-text explanations have a strong correlation with the dominant emotion
elicited by the headlines. The free-text explanations also contain more
sentimental context than the news headlines alone and can serve as a better
input to emotion classification models. Therefore, in this work we explored
generating emotion explanations from headlines by training a
sequence-to-sequence transformer model and by using pretrained large language
model, ChatGPT (GPT-4). We then used the generated emotion explanations for
emotion classification. In addition, we also experimented with training the
pretrained T5 model for the intermediate task of explanation generation before
fine-tuning it for emotion classification. Using McNemar's significance test,
methods that incorporate GPT-generated free-text emotion explanations
demonstrated significant improvement (P-value < 0.05) in emotion classification
from headlines, compared to methods that only use headlines. This underscores
the value of using intermediate free-text explanations for emotion prediction
tasks with headlines.
