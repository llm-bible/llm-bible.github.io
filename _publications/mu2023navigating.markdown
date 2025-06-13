---
layout: publication
title: 'Navigating Prompt Complexity For Zero-shot Classification: A Study Of Large Language Models In Computational Social Science'
authors: Yida Mu, Ben P. Wu, William Thorne, Ambrose Robinson, Nikolaos Aletras, Carolina Scarton, Kalina Bontcheva, Xingyi Song
conference: "Arxiv"
year: 2023
bibkey: mu2023navigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14310"}
tags: ['Transformer', 'GPT', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Prompting']
---
Instruction-tuned Large Language Models (LLMs) have exhibited impressive
language understanding and the capacity to generate responses that follow
specific prompts. However, due to the computational demands associated with
training these models, their applications often adopt a zero-shot setting. In
this paper, we evaluate the zero-shot performance of two publicly accessible
LLMs, ChatGPT and OpenAssistant, in the context of six Computational Social
Science classification tasks, while also investigating the effects of various
prompting strategies. Our experiments investigate the impact of prompt
complexity, including the effect of incorporating label definitions into the
prompt; use of synonyms for label names; and the influence of integrating past
memories during foundation model training. The findings indicate that in a
zero-shot setting, current LLMs are unable to match the performance of smaller,
fine-tuned baseline transformer models (such as BERT-large). Additionally, we
find that different prompting strategies can significantly affect
classification accuracy, with variations in accuracy and F1 scores exceeding
10%.
