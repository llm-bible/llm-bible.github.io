---
layout: publication
title: "Knowledge-based Consistency Testing Of Large Language Models"
authors: Rajan Sai Sathiesh, Soremekun Ezekiel, Chattopadhyay Sudipta
conference: "Arxiv"
year: 2024
bibkey: rajan2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12830"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
In this work we systematically expose and measure the inconsistency and knowledge gaps of Large Language Models (LLMs). Specifically we propose an automated testing framework (called KONTEST) which leverages a knowledge graph to construct test cases. KONTEST probes and measures the inconsistencies in the LLMs knowledge of the world via a combination of semantically-equivalent queries and test oracles (metamorphic or ontological oracle). KONTEST further mitigates knowledge gaps via a weighted LLM model ensemble. Using four state-of-the-art LLMs (Falcon Gemini GPT3.5 and Llama2) we show that KONTEST generates 19.237; error inducing inputs (1917 errors from 9983 test inputs). It also reveals a 16.537; knowledge gap across all tested LLMs. KONTESTs mitigation method reduces LLM knowledge gap by 32.4837;. Our ablation study further shows that GPT3.5 is not suitable for knowledge-based consistency testing because it is only 6037;-6837; effective in knowledge construction.
