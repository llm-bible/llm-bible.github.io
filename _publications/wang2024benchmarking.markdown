---
layout: publication
title: UBENCH: Benchmarking Uncertainty In Large Language Models With Multiple Choice Questions
authors: Wang Xunzhi, Zhang Zhuowei, Li Qiongyu, Chen Gaonan, Hu Mengting, Li Zhiyu, Luo Bitong, Gao Hang, Han Zhixin, Wang Haotian
conference: "Arxiv"
year: 2024
bibkey: wang2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12784"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Tools']
---
The rapid development of large language models (LLMs) has shown promising practical results. However their low interpretability often leads to errors in unforeseen circumstances limiting their utility. Many works have focused on creating comprehensive evaluation systems but previous benchmarks have primarily assessed problem-solving abilities while neglecting the responses uncertainty which may result in unreliability. Recent methods for measuring LLM reliability are resource-intensive and unable to test black-box models. To address this we propose UBENCH a comprehensive benchmark for evaluating LLM reliability. UBENCH includes 3978 multiple-choice questions covering knowledge language understanding and reasoning abilities. Experimental results show that UBENCH has achieved state-of-the-art performance while its single-sampling method significantly saves computational resources compared to baseline methods that require multiple samplings. Additionally based on UBENCH we evaluate the reliability of 15 popular LLMs finding GLM4 to be the most outstanding closely followed by GPT-4. We also explore the impact of Chain-of-Thought prompts role-playing prompts option order and temperature on LLM reliability analyzing the varying effects on different LLMs.
