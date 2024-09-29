---
layout: publication
title: RuleR Improving LLM Controllability by Rule-based Data Recycling
authors: Li Ming, Chen Han, Wang Chenguang, Nguyen Dang, Li Dianqi, Zhou Tianyi
conference: "Arxiv"
year: 2024
bibkey: li2024ruler
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15938"}
  - {name: "Code", url: "https://github.com/MingLiiii/RuleR"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) still lack delicate controllability over their responses which is critical to enhancing their performance and the user experience. However curating supervised fine-tuning (SFT) datasets to improve LLM controllability usually relies on human experts or proprietary LLMs which requires additional costs. To bridge this gap we propose Rule-based Data Recycling (RuleR) a data augmentation method incorporating multiple constraints into the original data samples according to predefined rules which creates new training tasks to consolidate the controllability of LLMs. Instead of creating new data from scratch RuleR recycles existing data by simply applying rule-based edits to their responses and appending the rule-instructions in their original instructions. Experimental results demonstrate RuleRs effectiveness in improving LLM controllability while maintaining general instruction-following capabilities. The code will be released on https://github.com/MingLiiii/RuleR.
