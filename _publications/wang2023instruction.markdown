---
layout: publication
title: Instructta Instruction45;tuned Targeted Attack For Large Vision45;language Models
authors: Wang Xunguang, Ji Zhenlan, Ma Pingchuan, Li Zongjie, Wang Shuai
conference: "Arxiv"
year: 2023
bibkey: wang2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01886"}
  - {name: "Code", url: "https://github.com/xunguangwang/InstructTA"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security']
---
Large vision45;language models (LVLMs) have demonstrated their incredible capability in image understanding and response generation. However this rich visual interaction also makes LVLMs vulnerable to adversarial examples. In this paper we formulate a novel and practical targeted attack scenario that the adversary can only know the vision encoder of the victim LVLM without the knowledge of its prompts (which are often proprietary for service providers and not publicly available) and its underlying large language model (LLM). This practical setting poses challenges to the cross45;prompt and cross45;model transferability of targeted adversarial attack which aims to confuse the LVLM to output a response that is semantically similar to the attackers chosen target text. To this end we propose an instruction45;tuned targeted attack (dubbed textsc123;InstructTA125;) to deliver the targeted adversarial attack on LVLMs with high transferability. Initially we utilize a public text45;to45;image generative model to reverse the target response into a target image and employ GPT45;4 to infer a reasonable instruction boldsymbol123;p125;^prime from the target response. We then form a local surrogate model (sharing the same vision encoder with the victim LVLM) to extract instruction45;aware features of an adversarial image example and the target image and minimize the distance between these two features to optimize the adversarial example. To further improve the transferability with instruction tuning we augment the instruction boldsymbol123;p125;^prime with instructions paraphrased from GPT45;4. Extensive experiments demonstrate the superiority of our proposed method in targeted attack performance and transferability. The code is available at https://github.com/xunguangwang/InstructTA.
