---
layout: publication
title: Sciglm Training Scientific Language Models With Self45;reflective Instruction Annotation And Tuning
authors: Zhang Dan, Hu Ziniu, Zhoubian Sining, Du Zhengxiao, Yang Kaiyu, Wang Zihan, Yue Yisong, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2024
bibkey: zhang2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07950"}
  - {name: "Code", url: "https://github.com/THUDM/SciGLM"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have shown promise in assisting scientific discovery. However such applications are currently limited by LLMs deficiencies in understanding intricate scientific concepts deriving symbolic equations and solving advanced numerical calculations. To bridge these gaps we introduce SciGLM a suite of scientific language models able to conduct college45;level scientific reasoning. Central to our approach is a novel self45;reflective instruction annotation framework to address the data scarcity challenge in the science domain. This framework leverages existing LLMs to generate step45;by45;step reasoning for unlabelled scientific questions followed by a process of self45;reflective critic45;and45;revise. Applying this framework we curated SciInstruct a diverse and high45;quality dataset encompassing physics chemistry math and formal proofs. We fine45;tuned the ChatGLM family of language models with SciInstruct enhancing their scientific and mathematical reasoning capabilities. Remarkably the SciGLM consistently improves both the base model (ChatGLM345;6B45;Base) by 4.8737; and larger45;scale models (32B) by 2.6737; without sacrificing the language understanding capabilities of the base model. This makes SciGLM a suitable foundational model to facilitate diverse scientific discovery tasks. For the benefit of the wider research community we release SciInstruct and SciGLM alongside a self45;reflective framework and fine45;tuning code at https://github.com/THUDM/SciGLM.
