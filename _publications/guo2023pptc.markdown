---
layout: publication
title: PPTC Benchmark Evaluating Large Language Models For Powerpoint Task Completion
authors: Guo Yiduo, Zhang Zekai, Liang Yaobo, Zhao Dongyan, Duan Nan
conference: "Arxiv"
year: 2023
bibkey: guo2023pptc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01767"}
  - {name: "Code", url: "https://github.com/gydpku/PPTC&#125;"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Recent evaluations of Large Language Models (LLMs) have centered around testing their zero45;shot/few45;shot capabilities for basic natural language tasks and their ability to translate instructions into tool APIs. However the evaluation of LLMs utilizing complex tools to finish multi45;turn multi45;modal instructions in a complex multi45;modal environment has not been investigated. To address this gap we introduce the PowerPoint Task Completion (PPTC) benchmark to assess LLMs ability to create and edit PPT files based on user instructions. It contains 279 multi45;turn sessions covering diverse topics and hundreds of instructions involving multi45;modal operations. We also propose the PPTX45;Match Evaluation System that evaluates if LLMs finish the instruction based on the prediction file rather than the label API sequence thus it supports various LLM45;generated API sequences. We measure 3 closed LLMs and 6 open45;source LLMs. The results show that GPT45;4 outperforms other LLMs with 75.137; accuracy in single45;turn dialogue testing but faces challenges in completing entire sessions achieving just 637; session accuracy. We find three main error causes in our benchmark error accumulation in the multi45;turn session long PPT template processing and multi45;modality perception. These pose great challenges for future LLM and agent systems. We release the data code and evaluation system of PPTC at url123;https://github.com/gydpku/PPTC&#125;.
