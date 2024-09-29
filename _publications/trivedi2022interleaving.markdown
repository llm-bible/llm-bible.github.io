---
layout: publication
title: Interleaving Retrieval With Chain45;of45;thought Reasoning For Knowledge45;intensive Multi45;step Questions
authors: Trivedi Harsh, Balasubramanian Niranjan, Khot Tushar, Sabharwal Ashish
conference: "Arxiv"
year: 2022
bibkey: trivedi2022interleaving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10509"}
  - {name: "Code", url: "https://github.com/stonybrooknlp/ircot&#125;"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Prompting45;based large language models (LLMs) are surprisingly powerful at generating natural language reasoning steps or Chains45;of45;Thoughts (CoT) for multi45;step question answering (QA). They struggle however when the necessary knowledge is either unavailable to the LLM or not up45;to45;date within its parameters. While using the question to retrieve relevant text from an external knowledge source helps LLMs we observe that this one45;step retrieve45;and45;read approach is insufficient for multi45;step QA. Here textit123;what to retrieve125; depends on textit123;what has already been derived125; which in turn may depend on textit123;what was previously retrieved125;. To address this we propose IRCoT a new approach for multi45;step QA that interleaves retrieval with steps (sentences) in a CoT guiding the retrieval with CoT and in turn using retrieved results to improve CoT. Using IRCoT with GPT3 substantially improves retrieval (up to 21 points) as well as downstream QA (up to 15 points) on four datasets HotpotQA 2WikiMultihopQA MuSiQue and IIRC. We observe similar substantial gains in out45;of45;distribution (OOD) settings as well as with much smaller models such as Flan45;T545;large without additional training. IRCoT reduces model hallucination resulting in factually more accurate CoT reasoning. Code data and prompts are available at url123;https://github.com/stonybrooknlp/ircot&#125;
