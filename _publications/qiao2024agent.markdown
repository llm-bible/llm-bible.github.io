---
layout: publication
title: Agent Planning With World Knowledge Model
authors: Qiao Shuofei, Fang Runnan, Zhang Ningyu, Zhu Yuqi, Chen Xiang, Deng Shumin, Jiang Yong, Xie Pengjun, Huang Fei, Chen Huajun
conference: "Arxiv"
year: 2024
bibkey: qiao2024agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14205"}
  - {name: "Code", url: "https://github.com/zjunlp/WKM"}
tags: ['Agentic', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Recent endeavors towards directly using large language models (LLMs) as agent models to execute interactive planning tasks have shown commendable results. Despite their achievements however they still struggle with brainless trial45;and45;error in global planning and generating hallucinatory actions in local planning due to their poor understanding of the real physical world. Imitating humans mental world knowledge model which provides global prior knowledge before the task and maintains local dynamic knowledge during the task in this paper we introduce parametric World Knowledge Model (WKM) to facilitate agent planning. Concretely we steer the agent model to self45;synthesize knowledge from both expert and sampled trajectories. Then we develop WKM providing prior task knowledge to guide the global planning and dynamic state knowledge to assist the local planning. Experimental results on three complex real45;world simulated datasets with three state45;of45;the45;art open45;source LLMs Mistral45;7B Gemma45;7B and Llama45;345;8B demonstrate that our method can achieve superior performance compared to various strong baselines. Besides we analyze to illustrate that our WKM can effectively alleviate the blind trial45;and45;error and hallucinatory action issues providing strong support for the agents understanding of the world. Other interesting findings include 1) our instance45;level task knowledge can generalize better to unseen tasks 2) weak WKM can guide strong agent model planning and 3) unified WKM training has promising potential for further development. Code will be available at https://github.com/zjunlp/WKM.
