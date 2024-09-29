---
layout: publication
title: L2ceval: Evaluating Language-to-code Generation Capabilities Of Large Language Models
authors: Ni Ansong, Yin Pengcheng, Zhao Yilun, Riddell Martin, Feng Troy, Shen Rui, Yin Stephen, Liu Ye, Yavuz Semih, Xiong Caiming, Joty Shafiq, Zhou Yingbo, Radev Dragomir, Cohan Arman
conference: "Arxiv"
year: 2023
bibkey: ni2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17446"}
tags: ['Applications', 'Few Shot', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Recently large language models (LLMs) especially those that are pretrained on code have demonstrated strong capabilities in generating programs from natural language inputs in a few-shot or even zero-shot manner. Despite promising results there is a notable lack of a comprehensive evaluation of these models language-to-code generation capabilities. Existing studies often focus on specific tasks model architectures or learning paradigms leading to a fragmented understanding of the overall landscape. In this work we present L2CEval a systematic evaluation of the language-to-code generation capabilities of LLMs on 7 tasks across the domain spectrum of semantic parsing math reasoning and Python programming analyzing the factors that potentially affect their performance such as model size pretraining data instruction tuning and different prompting methods. In addition to assessing model performance we measure confidence calibration for the models and conduct human evaluations of the output programs. This enables us to identify and analyze the typical failure modes across various tasks and models. L2CEval offers a comprehensive understanding of the capabilities and limitations of LLMs in language-to-code generation. We also release the evaluation framework and all model outputs hoping to lay the groundwork for further future research in this domain.
