---
layout: publication
title: 'Beyond The Reported Cutoff: Where Large Language Models Fall Short On Financial Knowledge'
authors: Agam Shah, Liqin Ye, Sebastian Jaskowski, Wei Xu, Sudheer Chava
conference: "Arxiv"
year: 2025
bibkey: shah2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00042'}
tags: ['Attention Mechanism', 'Prompting', 'Model Architecture']
---
Large Language Models (LLMs) are frequently utilized as sources of knowledge
for question-answering. While it is known that LLMs may lack access to
real-time data or newer data produced after the model's cutoff date, it is less
clear how their knowledge spans across historical information. In this study,
we assess the breadth of LLMs' knowledge using financial data of U.S. publicly
traded companies by evaluating more than 197k questions and comparing model
responses to factual data. We further explore the impact of company
characteristics, such as size, retail investment, institutional attention, and
readability of financial filings, on the accuracy of knowledge represented in
LLMs. Our results reveal that LLMs are less informed about past financial
performance, but they display a stronger awareness of larger companies and more
recent information. Interestingly, at the same time, our analysis also reveals
that LLMs are more likely to hallucinate for larger companies, especially for
data from more recent years. We will make the code, prompts, and model outputs
public upon the publication of the work.
