---
layout: publication
title: 'Defan: Definitive Answer Dataset For Llms Hallucination Evaluation'
authors: Rahman A B M Ashikur, Anwar Saeed, Usman Muhammad, Mian Ajmal
conference: "Arxiv"
year: 2024
bibkey: rahman2024definitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09155"}
  - {name: "Code", url: "https://github.com/ashikiut/DefAn}{https://github.com/ashikiut/DefAn"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
"Large Language Models (LLMs) have demonstrated remarkable capabilities, revolutionizing the integration of AI in daily life applications. However, they are prone to hallucinations, generating claims that contradict established facts, deviating from prompts, and producing inconsistent responses when the same prompt is presented multiple times. Addressing these issues is challenging due to the lack of comprehensive and easily assessable benchmark datasets. Most existing datasets are small and rely on multiple-choice questions, which are inadequate for evaluating the generative prowess of LLMs. To measure hallucination in LLMs, this paper introduces a comprehensive benchmark dataset comprising over 75,000 prompts across eight domains. These prompts are designed to elicit definitive, concise, and informative answers. The dataset is divided into two segments: one publicly available for testing and assessing LLM performance and a hidden segment for benchmarking various LLMs. In our experiments, we tested six LLMs-GPT-3.5, LLama 2, LLama 3, Gemini, Mixtral, and Zephyr-revealing that overall factual hallucination ranges from 59&#37; to 82&#37; on the public dataset and 57&#37; to 76&#37; in the hidden benchmark. Prompt misalignment hallucination ranges from 6&#37; to 95&#37; in the public dataset and 17&#37; to 94&#37; in the hidden counterpart. Average consistency ranges from 21&#37; to 61&#37; and 22&#37; to 63&#37;, respectively. Domain-wise analysis shows that LLM performance significantly deteriorates when asked for specific numeric information while performing moderately with person, location, and date queries. Our dataset demonstrates its efficacy and serves as a comprehensive benchmark for LLM performance evaluation. Our dataset and LLMs responses are available at \href\{https://github.com/ashikiut/DefAn\}\{https://github.com/ashikiut/DefAn\}."
