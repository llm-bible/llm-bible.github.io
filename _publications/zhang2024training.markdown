---
layout: publication
title: 'Sciglm: Training Scientific Language Models With Self-reflective Instruction Annotation And Tuning'
authors: Zhang Dan, Hu Ziniu, Zhoubian Sining, Du Zhengxiao, Yang Kaiyu, Wang Zihan, Yue Yisong, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2024
bibkey: zhang2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07950"}
  - {name: "Code", url: "https://github.com/THUDM/SciGLM"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have shown promise in assisting scientific discovery. However such applications are currently limited by LLMs deficiencies in understanding intricate scientific concepts deriving symbolic equations and solving advanced numerical calculations. To bridge these gaps we introduce SciGLM a suite of scientific language models able to conduct college-level scientific reasoning. Central to our approach is a novel self-reflective instruction annotation framework to address the data scarcity challenge in the science domain. This framework leverages existing LLMs to generate step-by-step reasoning for unlabelled scientific questions followed by a process of self-reflective critic-and-revise. Applying this framework we curated SciInstruct a diverse and high-quality dataset encompassing physics chemistry math and formal proofs. We fine-tuned the ChatGLM family of language models with SciInstruct enhancing their scientific and mathematical reasoning capabilities. Remarkably the SciGLM consistently improves both the base model (ChatGLM3-6B-Base) by 4.8737; and larger-scale models (32B) by 2.6737; without sacrificing the language understanding capabilities of the base model. This makes SciGLM a suitable foundational model to facilitate diverse scientific discovery tasks. For the benefit of the wider research community we release SciInstruct and SciGLM alongside a self-reflective framework and fine-tuning code at https://github.com/THUDM/SciGLM."
