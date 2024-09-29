---
layout: publication
title: Bioinstruct Instruction Tuning Of Large Language Models For Biomedical Natural Language Processing
authors: Tran Hieu, Yang Zhichao, Yao Zonghai, Yu Hong
conference: "Arxiv"
year: 2023
bibkey: tran2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19975"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting']
---
To enhance the performance of large language models (LLMs) in biomedical natural language processing (BioNLP) by introducing a domain45;specific instruction dataset and examining its impact when combined with multi45;task learning principles. We created the BioInstruct comprising 25005 instructions to instruction45;tune LLMs(LLaMA 1 amp; 2 7B amp; 13B version). The instructions were created by prompting the GPT45;4 language model with three45;seed samples randomly drawn from an 80 human curated instructions. We employed Low45;Rank Adaptation(LoRA) for parameter45;efficient fine45;tuning. We then evaluated these instruction45;tuned LLMs on several BioNLP tasks which can be grouped into three major categories question answering(QA) information extraction(IE) and text generation(GEN). We also examined whether categories(e.g. QA IE and generation) of instructions impact model performance. Comparing with LLMs without instruction45;tuned our instruction45;tuned LLMs demonstrated marked performance gains 17.337; in QA 5.737; in IE and 9637; in Generation tasks. Our 7B45;parameter instruction45;tuned LLaMA 1 model was competitive or even surpassed other LLMs in the biomedical domain that were also fine45;tuned from LLaMA 1 with vast domain45;specific data or a variety of tasks. Our results also show that the performance gain is significantly higher when instruction fine45;tuning is conducted with closely related tasks. Our findings align with the observations of multi45;task learning suggesting the synergies between two tasks. The BioInstruct dataset serves as a valuable resource and instruction tuned LLMs lead to the best performing BioNLP applications.
