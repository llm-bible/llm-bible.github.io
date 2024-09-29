---
layout: publication
title: Enhance Lifelong Model Editing With Continuous Data45;adapter Association
authors: Li Jiaang, Wang Quan, Wang Zhongnan, Zhang Yongdong, Mao Zhendong
conference: "Arxiv"
year: 2024
bibkey: li2024enhance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11869"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Security']
---
Large language models (LLMs) require model editing to efficiently update specific knowledge within them and avoid factual errors. Most model editing methods are solely designed for single45;time use and lead to a significant forgetting effect after sequential edits over time referred to as lifelong editing. Current approaches manage sequential edits by freezing original parameters and allocating new adapters for each knowledge modification. However these methods lack robustness to minor input variations. To address this challenge we propose ELDER textbf123;E125;nhancing textbf123;L125;ifelong motextbf123;D125;el textbf123;E125;diting with mixtutextbf123;R125;e of Low45;Rank Adapter (LoRA). ELDER is an adaptive approach that integrates multiple LoRAs through a router network. It learns to create a continuous and smooth association between data and adapters thereby enhancing robustness and generalization to semantically equivalent inputs. Additionally we introduce a novel loss to help learn associations between adapter allocations and edit semantics. A deferral mechanism is also proposed to retain the original LLM capabilities post45;edit. Extensive experiments on GPT45;2 XL and LLaMA245;7B demonstrate that ELDER effectively edits models in the lifelong setting and exhibits strong scalability while retaining LLMs general abilities on downstream tasks.
