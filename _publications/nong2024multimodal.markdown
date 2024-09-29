---
layout: publication
title: Mobileflow A Multimodal LLM For Mobile GUI Agent
authors: Nong Songqin, Zhu Jiali, Wu Rui, Jin Jiongchao, Shan Shuo, Huang Xiutian, Xu Wenhao
conference: "Arxiv"
year: 2024
bibkey: nong2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04346"}
tags: ['Agentic', 'Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Currently the integration of mobile Graphical User Interfaces (GUIs) is ubiquitous in most peoples daily lives. And the ongoing evolution of multimodal large45;scale models such as GPT45;4v Qwen45;VL45;Max has significantly bolstered the capabilities of GUI comprehension and user action analysis showcasing the potentiality of intelligent GUI assistants. However current GUI Agents often need to access page layout information through calling system APIs which may pose privacy risks. Fixing GUI (such as mobile interfaces) to a certain low resolution might result in the loss of fine45;grained image details. At the same time the multimodal large models built for GUI Agents currently have poor understanding and decision45;making abilities for Chinese GUI interfaces making them difficult to apply to a large number of Chinese apps. This paper introduces MobileFlow a multimodal large language model meticulously crafted for mobile GUI agents. Transforming from the open45;source model Qwen45;VL45;Chat into GUI domain MobileFlow contains approximately 21 billion parameters and is equipped with novel hybrid visual encoders making it possible for variable resolutions of image inputs and good support for multilingual GUI. By incorporating Mixture of Experts (MoE) expansions and pioneering alignment training strategies MobileFlow has the capacity to fully interpret image data and comprehend user instructions for GUI interaction tasks. Finally MobileFlow outperforms Qwen45;VL45;Max and GPT45;4v in terms of task execution by GUI agents on both public and our proposed evaluation metrics and has been successfully deployed in real45;world business contexts proving its effectiveness for practical applications.
