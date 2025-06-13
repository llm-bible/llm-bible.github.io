---
layout: publication
title: 'Normad: A Framework For Measuring The Cultural Adaptability Of Large Language Models'
authors: Abhinav Rao, Akhila Yerukola, Vishwa Shah, Katharina Reinecke, Maarten Sap
conference: "Arxiv"
year: 2024
bibkey: rao2024framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12464"}
tags: ['Tools']
---
To be effectively and safely deployed to global user populations, large
language models (LLMs) may need to adapt outputs to user values and cultures,
not just know about them. We introduce NormAd, an evaluation framework to
assess LLMs' cultural adaptability, specifically measuring their ability to
judge social acceptability across varying levels of cultural norm specificity,
from abstract values to explicit social norms. As an instantiation of our
framework, we create NormAd-Eti, a benchmark of 2.6k situational descriptions
representing social-etiquette related cultural norms from 75 countries. Through
comprehensive experiments on NormAd-Eti, we find that LLMs struggle to
accurately judge social acceptability across these varying degrees of cultural
contexts and show stronger adaptability to English-centric cultures over those
from the Global South. Even in the simplest setting where the relevant social
norms are provided, the best LLMs' performance (< 82%) lags behind humans (>
95%). In settings with abstract values and country information, model
performance drops substantially (< 60%), while human accuracy remains high (>
90%). Furthermore, we find that models are better at recognizing socially
acceptable versus unacceptable situations. Our findings showcase the current
pitfalls in socio-cultural reasoning of LLMs which hinder their adaptability
for global audiences.
