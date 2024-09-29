---
layout: publication
title: 'X-LLM: Bootstrapping Advanced Large Language Models By Treating Multi-modalities As Foreign Languages'
authors: Chen Feilong, Han Minglun, Zhao Haozhi, Zhang Qingyang, Shi Jing, Xu Shuang, Xu Bo
conference: "Arxiv"
year: 2023
bibkey: chen2023x
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.04160"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
Large language models (LLMs) have demonstrated remarkable language abilities. GPT-4 based on advanced LLMs exhibits extraordinary multimodal capabilities beyond previous visual language models. We attribute this to the use of more advanced LLMs compared with previous multimodal models. Unfortunately the model architecture and training strategies of GPT-4 are unknown. To endow LLMs with multimodal capabilities we propose X-LLM which converts Multi-modalities (images speech videos) into foreign languages using X2L interfaces and inputs them into a large Language model (ChatGLM). Specifically X-LLM aligns multiple frozen single-modal encoders and a frozen LLM using X2L interfaces where X denotes multi-modalities such as image speech and videos and L denotes languages. X-LLMs training consists of three stages (1) Converting Multimodal Information The first stage trains each X2L interface to align with its respective single-modal encoder separately to convert multimodal information into languages. (2) Aligning X2L representations with the LLM single-modal encoders are aligned with the LLM through X2L interfaces independently. (3) Integrating multiple modalities all single-modal encoders are aligned with the LLM through X2L interfaces to integrate multimodal capabilities into the LLM. Our experiments show that X-LLM demonstrates impressive multimodel chat abilities sometimes exhibiting the behaviors of multimodal GPT-4 on unseen images/instructions and yields a 84.537; relative score compared with GPT-4 on a synthetic multimodal instruction-following dataset. And we also conduct quantitative tests on using LLM for ASR and multimodal ASR hoping to promote the era of LLM-based speech recognition.
