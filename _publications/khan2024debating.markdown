---
layout: publication
title: Debating With More Persuasive Llms Leads To More Truthful Answers
authors: Khan Akbir, Hughes John, Valentine Dan, Ruis Laura, Sachan Kshitij, Radhakrishnan Ansh, Grefenstette Edward, Bowman Samuel R., Rocktäschel Tim, Perez Ethan
conference: "Arxiv"
year: 2024
bibkey: khan2024debating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06782"}
tags: ['Ethics And Bias', 'RAG']
---
Common methods for aligning large language models (LLMs) with desired behaviour heavily rely on human45;labelled data. However as models grow increasingly sophisticated they will surpass human expertise and the role of human evaluation will evolve into non45;experts overseeing experts. In anticipation of this we ask can weaker models assess the correctness of stronger models We investigate this question in an analogous setting where stronger models (experts) possess the necessary information to answer questions and weaker models (non45;experts) lack this information. The method we evaluate is debate where two LLM experts each argue for a different answer and a non45;expert selects the answer. We find that debate consistently helps both non45;expert models and humans answer questions achieving 7637; and 8837; accuracy respectively (naive baselines obtain 4837; and 6037;). Furthermore optimising expert debaters for persuasiveness in an unsupervised manner improves non45;expert ability to identify the truth in debates. Our results provide encouraging empirical evidence for the viability of aligning models with debate in the absence of ground truth.
