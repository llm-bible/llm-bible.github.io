---
layout: publication
title: 'Agrogpt: Efficient Agricultural Vision-language Model With Expert Tuning'
authors: Muhammad Awais, Ali Husain Salem Abdulla Alharthi, Amandeep Kumar, Hisham Cholakkal, Rao Muhammad Anwer
conference: "Arxiv"
year: 2024
bibkey: awais2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.08405'}
  - {name: "Code", url: 'https://github.com/awaisrauf/agroGPT'}
tags: ['Has Code', 'Model Architecture', 'Tools', 'GPT', 'Fine-Tuning', 'Multimodal Models']
---
Significant progress has been made in advancing large multimodal
conversational models (LMMs), capitalizing on vast repositories of image-text
data available online. Despite this progress, these models often encounter
substantial domain gaps, hindering their ability to engage in complex
conversations across new domains. Recent efforts have aimed to mitigate this
issue, albeit relying on domain-specific image-text data to curate
instruction-tuning data. However, many domains, such as agriculture, lack such
vision-language data. In this work, we propose an approach to construct
instruction-tuning data that harnesses vision-only data for the agriculture
domain. We utilize diverse agricultural datasets spanning multiple domains,
curate class-specific information, and employ large language models (LLMs) to
construct an expert-tuning set, resulting in a 70k expert-tuning dataset called
AgroInstruct. Subsequently, we expert-tuned and created AgroGPT, an efficient
LMM that can hold complex agriculture-related conversations and provide useful
insights. We also develop AgroEvals for evaluation and compare \{AgroGPT's\}
performance with large open and closed-source models. \{AgroGPT\} excels at
identifying fine-grained agricultural concepts, can act as an agriculture
expert, and provides helpful information for multimodal agriculture questions.
The code, datasets, and models are available at
https://github.com/awaisrauf/agroGPT.
