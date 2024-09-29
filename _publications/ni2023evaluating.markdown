---
layout: publication
title: Evaluating the Robustness to Instructions of Large Language Models
authors: Ni Yuansheng, Jiang Sichao, Wu Xinyu, Shen Hui, Zhou Yuli
conference: "Arxiv"
year: 2023
bibkey: ni2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.14306"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Recently Instruction fine-tuning has risen to prominence as a potential method for enhancing the zero-shot capabilities of Large Language Models (LLMs) on novel tasks. This technique has shown an exceptional ability to boost the performance of moderately sized LLMs sometimes even reaching performance levels comparable to those of much larger model variants. The focus is on the robustness of instruction-tuned LLMs to seen and unseen tasks. We conducted an exploration of six models including Alpaca Vicuna WizardLM and Traditional Task-oriented Models(Flan-T5-XL/XXL T0++) using real-world relation extraction datasets as case studies. We carried out a comprehensive evaluation of these instruction-following LLMs which have been tuned based on open-domain instructions and task-oriented instructions. The main discussion is their performance and robustness towards instructions. We have observed that in most cases the models performance in dealing with unfamiliar instructions tends to worsen significantly and the robustness of the model for RE instructions deteriorates compared to QA. Further we discovered that up until a certain parameter size threshold (3B) the performance of the FLAN-T5 model improves as the parameter count increases. The robustness of different scales of FLAN-T5 models to RE instruction is worse than the robustness to QA instruction.
