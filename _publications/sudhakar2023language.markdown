---
layout: publication
title: 'Language Model-in-the-loop: Data Optimal Approach To Learn-to-recommend Actions In Text Games'
authors: Arjun Vaithilingam Sudhakar, Prasanna Parthasarathi, Janarthanan Rajendran, Sarath Chandar
conference: "Arxiv"
year: 2023
bibkey: sudhakar2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07687"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Large Language Models (LLMs) have demonstrated superior performance in
language understanding benchmarks. CALM, a popular approach, leverages
linguistic priors of LLMs -- GPT-2 -- for action candidate recommendations to
improve the performance in text games in Jericho without environment-provided
actions. However, CALM adapts GPT-2 with annotated human gameplays and keeps
the LLM fixed during the learning of the text based games. In this work, we
explore and evaluate updating LLM used for candidate recommendation during the
learning of the text based game as well to mitigate the reliance on the human
annotated gameplays, which are costly to acquire. We observe that by updating
the LLM during learning using carefully selected in-game transitions, we can
reduce the dependency on using human annotated game plays for fine-tuning the
LLMs. We conducted further analysis to study the transferability of the updated
LLMs and observed that transferring in-game trained models to other games did
not result in a consistent transfer.
