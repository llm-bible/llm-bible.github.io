---
layout: publication
title: 'Llms For Targeted Sentiment In News Headlines: Exploring The Descriptive-prescriptive Dilemma'
authors: Jana Juroš, Laura Majer, Jan Šnajder
conference: "Arxiv"
year: 2024
bibkey: juroš2024llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.00418'}
tags: ['Few-Shot', 'RAG', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
News headlines often evoke sentiment by intentionally portraying entities in
particular ways, making targeted sentiment analysis (TSA) of headlines a
worthwhile but difficult task. Due to its subjectivity, creating TSA datasets
can involve various annotation paradigms, from descriptive to prescriptive,
either encouraging or limiting subjectivity. LLMs are a good fit for TSA due to
their broad linguistic and world knowledge and in-context learning abilities,
yet their performance depends on prompt design. In this paper, we compare the
accuracy of state-of-the-art LLMs and fine-tuned encoder models for TSA of news
headlines using descriptive and prescriptive datasets across several languages.
Exploring the descriptive--prescriptive continuum, we analyze how performance
is affected by prompt prescriptiveness, ranging from plain zero-shot to
elaborate few-shot prompts. Finally, we evaluate the ability of LLMs to
quantify uncertainty via calibration error and comparison to human label
variation. We find that LLMs outperform fine-tuned encoders on descriptive
datasets, while calibration and F1-score generally improve with increased
prescriptiveness, yet the optimal level varies.
