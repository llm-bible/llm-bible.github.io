---
layout: publication
title: Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions
authors: Trivedi Harsh, Balasubramanian Niranjan, Khot Tushar, Sabharwal Ashish
conference: "Arxiv"
year: 2022
bibkey: trivedi2022interleaving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10509"}
  - {name: "Code", url: "https://github.com/stonybrooknlp/ircot"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Prompting-based large language models (LLMs) are surprisingly powerful at generating natural language reasoning steps or Chains-of-Thoughts (CoT) for multi-step question answering (QA). They struggle however when the necessary knowledge is either unavailable to the LLM or not up-to-date within its parameters. While using the question to retrieve relevant text from an external knowledge source helps LLMs we observe that this one-step retrieve-and-read approach is insufficient for multi-step QA. Here textitwhat to retrieve depends on textitwhat has already been derived which in turn may depend on textitwhat was previously retrieved. To address this we propose IRCoT a new approach for multi-step QA that interleaves retrieval with steps (sentences) in a CoT guiding the retrieval with CoT and in turn using retrieved results to improve CoT. Using IRCoT with GPT3 substantially improves retrieval (up to 21 points) as well as downstream QA (up to 15 points) on four datasets HotpotQA 2WikiMultihopQA MuSiQue and IIRC. We observe similar substantial gains in out-of-distribution (OOD) settings as well as with much smaller models such as Flan-T5-large without additional training. IRCoT reduces model hallucination resulting in factually more accurate CoT reasoning. Code data and prompts are available at url https://github.com/stonybrooknlp/ircot
