---
layout: publication
title: Prompt Perturbation Consistency Learning For Robust Language Models
authors: Qiang Yao, Nandi Subhrangshu, Mehrabi Ninareh, Steeg Greg Ver, Kumar Anoop, Rumshisky Anna, Galstyan Aram
conference: "Arxiv"
year: 2024
bibkey: qiang2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15833"}
tags: ['Applications', 'Prompting', 'RAG', 'Security']
---
Large language models (LLMs) have demonstrated impressive performance on a number of natural language processing tasks such as question answering and text summarization. However their performance on sequence labeling tasks such as intent classification and slot filling (IC45;SF) which is a central component in personal assistant systems lags significantly behind discriminative models. Furthermore there is a lack of substantive research on the robustness of LLMs to various perturbations in the input prompts. The contributions of this paper are three45;fold. First we show that fine45;tuning sufficiently large LLMs can produce IC45;SF performance comparable to discriminative models. Next we systematically analyze the performance deterioration of those fine45;tuned models due to three distinct yet relevant types of input perturbations 45; oronyms synonyms and paraphrasing. Finally we propose an efficient mitigation approach Prompt Perturbation Consistency Learning (PPCL) which works by regularizing the divergence between losses from clean and perturbed samples. Our experiments demonstrate that PPCL can recover on average 5937; and 6937; of the performance drop for IC and SF tasks respectively. Furthermore PPCL beats the data augmentation approach while using ten times fewer augmented data samples.
