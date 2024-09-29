---
layout: publication
title: Optimizing Language Augmentation For Multilingual Large Language Models: A Case Study On Korean
authors: Choi Changsu, Jeong Yongbin, Park Seoyoon, Won Inho, Lim Hyeonseok, Kim Sangmin, Kang Yejee, Yoon Chanhyuk, Park Jaewan, Lee Yiseul, Lee Hyejin, Hahm Younggyun, Kim Hansaem, Lim Kyungtae
conference: "Arxiv"
year: 2024
bibkey: choi2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10882"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) use pretraining to predict the subsequent word; however their expansion requires significant computing resources. Numerous big tech companies and research institutes have developed multilingual LLMs (MLLMs) to meet current demands overlooking less-resourced languages (LRLs). This study proposed three strategies to enhance the performance of LRLs based on the publicly available MLLMs. First the MLLM vocabularies of LRLs were expanded to enhance expressiveness. Second bilingual data were used for pretraining to align the high- and less-resourced languages. Third a high-quality small-scale instruction dataset was constructed and instruction-tuning was performed to augment the LRL. The experiments employed the Llama2 model and Korean was used as the LRL which was quantitatively evaluated against other developed LLMs across eight tasks. Furthermore a qualitative assessment was performed based on human evaluation and GPT4. Experimental results showed that our proposed Bllossom model exhibited superior performance in qualitative analyses compared to previously proposed Korean monolingual models.
