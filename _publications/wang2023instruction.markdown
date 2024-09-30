---
layout: publication
title: 'Instructta: Instruction-tuned Targeted Attack For Large Vision-language Models'
authors: Wang Xunguang, Ji Zhenlan, Ma Pingchuan, Li Zongjie, Wang Shuai
conference: "Arxiv"
year: 2023
bibkey: wang2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01886"}
  - {name: "Code", url: "https://github.com/xunguangwang/InstructTA"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Security']
---
Large vision-language models (LVLMs) have demonstrated their incredible capability in image understanding and response generation. However this rich visual interaction also makes LVLMs vulnerable to adversarial examples. In this paper we formulate a novel and practical targeted attack scenario that the adversary can only know the vision encoder of the victim LVLM without the knowledge of its prompts (which are often proprietary for service providers and not publicly available) and its underlying large language model (LLM). This practical setting poses challenges to the cross-prompt and cross-model transferability of targeted adversarial attack which aims to confuse the LVLM to output a response that is semantically similar to the attackers chosen target text. To this end we propose an instruction-tuned targeted attack (dubbed textscInstructTA) to deliver the targeted adversarial attack on LVLMs with high transferability. Initially we utilize a public text-to-image generative model to reverse the target response into a target image and employ GPT-4 to infer a reasonable instruction (^prime) from the target response. We then form a local surrogate model (sharing the same vision encoder with the victim LVLM) to extract instruction-aware features of an adversarial image example and the target image and minimize the distance between these two features to optimize the adversarial example. To further improve the transferability with instruction tuning we augment the instruction (^prime) with instructions paraphrased from GPT-4. Extensive experiments demonstrate the superiority of our proposed method in targeted attack performance and transferability. The code is available at https://github.com/xunguangwang/InstructTA."
