---
layout: publication
title: Doctorglm Fine45;tuning Your Chinese Doctor Is Not A Herculean Task
authors: Xiong Honglin, Wang Sheng, Zhu Yitao, Zhao Zihao, Liu Yuxiao, Huang Linlin, Wang Qian, Shen Dinggang
conference: "Arxiv"
year: 2023
bibkey: xiong2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01097"}
  - {name: "Code", url: "https://github.com/xionghonglin/DoctorGLM"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The recent progress of large language models (LLMs) including ChatGPT and GPT45;4 in comprehending and responding to human instructions has been remarkable. Nevertheless these models typically perform better in English and have not been explicitly trained for the medical domain resulting in suboptimal precision in diagnoses drug recommendations and other medical advice. Additionally training and deploying a dialogue model is still believed to be impossible for hospitals hindering the promotion of LLMs. To tackle these challenges we have collected databases of medical dialogues in Chinese with ChatGPTs help and adopted several techniques to train an easy45;deploy LLM. Remarkably we were able to fine45;tune the ChatGLM45;6B on a single A100 80G in 13 hours which means having a healthcare45;purpose LLM can be very affordable. DoctorGLM is currently an early45;stage engineering attempt and contain various mistakes. We are sharing it with the broader community to invite feedback and suggestions to improve its healthcare45;focused capabilities https://github.com/xionghonglin/DoctorGLM.
