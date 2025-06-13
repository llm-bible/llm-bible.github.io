---
layout: publication
title: 'Exploring The Use Of A Large Language Model For Data Extraction In Systematic Reviews: A Rapid Feasibility Study'
authors: Lena Schmidt, Kaitlyn Hair, Sergio Graziosi, Fiona Campbell, Claudia Kapp, Alireza Khanteymoori, Dawn Craig, Mark Engelbert, James Thomas
conference: "Proceedings of the 3rd Workshop on Augmented Intelligence for Technology-Assisted Reviews Systems (ALTARS 2024) Glasgow. https://ceur-ws.org/Vol-3832/paper2.pdf"
year: 2024
bibkey: schmidt2024exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.14445'}
tags: ['GPT', 'Tools', 'Model Architecture', 'Prompting', 'Survey Paper']
---
This paper describes a rapid feasibility study of using GPT-4, a large
language model (LLM), to (semi)automate data extraction in systematic reviews.
Despite the recent surge of interest in LLMs there is still a lack of
understanding of how to design LLM-based automation tools and how to robustly
evaluate their performance. During the 2023 Evidence Synthesis Hackathon we
conducted two feasibility studies. Firstly, to automatically extract study
characteristics from human clinical, animal, and social science domain studies.
We used two studies from each category for prompt-development; and ten for
evaluation. Secondly, we used the LLM to predict Participants, Interventions,
Controls and Outcomes (PICOs) labelled within 100 abstracts in the EBM-NLP
dataset. Overall, results indicated an accuracy of around 80%, with some
variability between domains (82% for human clinical, 80% for animal, and 72%
for studies of human social sciences). Causal inference methods and study
design were the data extraction items with the most errors. In the PICO study,
participants and intervention/control showed high accuracy (>80%), outcomes
were more challenging. Evaluation was done manually; scoring methods such as
BLEU and ROUGE showed limited value. We observed variability in the LLMs
predictions and changes in response quality. This paper presents a template for
future evaluations of LLMs in the context of data extraction for systematic
review automation. Our results show that there might be value in using LLMs,
for example as second or third reviewers. However, caution is advised when
integrating models such as GPT-4 into tools. Further research on stability and
reliability in practical settings is warranted for each type of data that is
processed by the LLM.
