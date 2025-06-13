---
layout: publication
title: 'Language Model Fine-tuning On Scaled Survey Data For Predicting Distributions Of Public Opinions'
authors: Joseph Suh, Erfan Jahanparast, Suhong Moon, Minwoo Kang, Serina Chang
conference: "Arxiv"
year: 2025
bibkey: suh2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16761"}
  - {name: "Code", url: "https://github.com/JosephJeesungSuh/subpop"}
tags: ['Training Techniques', 'Survey Paper', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
Large language models (LLMs) present novel opportunities in public opinion
research by predicting survey responses in advance during the early stages of
survey design. Prior methods steer LLMs via descriptions of subpopulations as
LLMs' input prompt, yet such prompt engineering approaches have struggled to
faithfully predict the distribution of survey responses from human subjects. In
this work, we propose directly fine-tuning LLMs to predict response
distributions by leveraging unique structural characteristics of survey data.
To enable fine-tuning, we curate SubPOP, a significantly scaled dataset of
3,362 questions and 70K subpopulation-response pairs from well-established
public opinion surveys. We show that fine-tuning on SubPOP greatly improves the
match between LLM predictions and human responses across various
subpopulations, reducing the LLM-human gap by up to 46% compared to baselines,
and achieves strong generalization to unseen surveys and subpopulations. Our
findings highlight the potential of survey-based fine-tuning to improve opinion
prediction for diverse, real-world subpopulations and therefore enable more
efficient survey designs. Our code is available at
https://github.com/JosephJeesungSuh/subpop.
