---
layout: publication
title: Harnessing The Power Of Prompt45;based Techniques For Generating School45;level Questions Using Large Language Models
authors: Maity Subhankar, Deroy Aniket, Sarkar Sudeshna
conference: "Arxiv"
year: 2023
bibkey: maity2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01032"}
  - {name: "Code", url: "https://github.com/my625/PromptQG"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Designing high45;quality educational questions is a challenging and time45;consuming task. In this work we propose a novel approach that utilizes prompt45;based techniques to generate descriptive and reasoning45;based questions. However current question45;answering (QA) datasets are inadequate for conducting our experiments on prompt45;based question generation (QG) in an educational setting. Therefore we curate a new QG dataset called EduProbe for school45;level subjects by leveraging the rich content of NCERT textbooks. We carefully annotate this dataset as quadruples of 1) Context a segment upon which the question is formed; 2) Long Prompt a long textual cue for the question (i.e. a longer sequence of words or phrases covering the main theme of the context); 3) Short Prompt a short textual cue for the question (i.e. a condensed representation of the key information or focus of the context); 4) Question a deep question that aligns with the context and is coherent with the prompts. We investigate several prompt45;based QG methods by fine45;tuning pre45;trained transformer45;based large language models (LLMs) namely PEGASUS T5 MBART and BART. Moreover we explore the performance of two general45;purpose pre45;trained LLMs such as Text45;Davinci45;003 and GPT45;3.545;Turbo without any further training. By performing automatic evaluation we show that T5 (with long prompt) outperforms all other models but still falls short of the human baseline. Under human evaluation criteria TextDavinci45;003 usually shows better results than other models under various prompt settings. Even in the case of human evaluation criteria QG models mostly fall short of the human baseline. Our code and dataset are available at https://github.com/my625/PromptQG
