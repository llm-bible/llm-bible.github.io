---
layout: publication
title: 'Prompting Large Language Models For Zero-shot Essay Scoring Via Multi-trait Specialization'
authors: Lee Sanwoo, Cai Yida, Meng Desong, Wang Ziyang, Wu Yunfang
conference: "Arxiv"
year: 2024
bibkey: lee2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04941"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Advances in automated essay scoring (AES) have traditionally relied on labeled essays, requiring tremendous cost and expertise for their acquisition. Recently, large language models (LLMs) have achieved great success in various tasks, but their potential is less explored in AES. In this paper, we propose Multi Trait Specialization (MTS), a zero-shot prompting framework to elicit essay scoring capabilities in LLMs. Specifically, we leverage ChatGPT to decompose writing proficiency into distinct traits and generate scoring criteria for each trait. Then, an LLM is prompted to extract trait scores from several conversational rounds, each round scoring one of the traits based on the scoring criteria. Finally, we derive the overall score via trait averaging and min-max scaling. Experimental results on two benchmark datasets demonstrate that MTS consistently outperforms straightforward prompting (Vanilla) in average QWK across all LLMs and datasets, with maximum gains of 0.437 on TOEFL11 and 0.355 on ASAP. Additionally, with the help of MTS, the small-sized Llama2-13b-chat substantially outperforms ChatGPT, facilitating an effective deployment in real applications.
