---
layout: publication
title: 'Harnessing The Power Of Prompt-based Techniques For Generating School-level Questions Using Large Language Models'
authors: Maity Subhankar, Deroy Aniket, Sarkar Sudeshna
conference: "Arxiv"
year: 2023
bibkey: maity2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01032"}
  - {name: "Code", url: "https://github.com/my625/PromptQG"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Designing high-quality educational questions is a challenging and time-consuming task. In this work we propose a novel approach that utilizes prompt-based techniques to generate descriptive and reasoning-based questions. However current question-answering (QA) datasets are inadequate for conducting our experiments on prompt-based question generation (QG) in an educational setting. Therefore we curate a new QG dataset called EduProbe for school-level subjects by leveraging the rich content of NCERT textbooks. We carefully annotate this dataset as quadruples of 1) Context a segment upon which the question is formed; 2) Long Prompt a long textual cue for the question (i.e. a longer sequence of words or phrases covering the main theme of the context); 3) Short Prompt a short textual cue for the question (i.e. a condensed representation of the key information or focus of the context); 4) Question a deep question that aligns with the context and is coherent with the prompts. We investigate several prompt-based QG methods by fine-tuning pre-trained transformer-based large language models (LLMs) namely PEGASUS T5 MBART and BART. Moreover we explore the performance of two general-purpose pre-trained LLMs such as Text-Davinci-003 and GPT-3.5-Turbo without any further training. By performing automatic evaluation we show that T5 (with long prompt) outperforms all other models but still falls short of the human baseline. Under human evaluation criteria TextDavinci-003 usually shows better results than other models under various prompt settings. Even in the case of human evaluation criteria QG models mostly fall short of the human baseline. Our code and dataset are available at https://github.com/my625/PromptQG"
