---
layout: publication
title: Prompting Large Language Models For Zero-shot Clinical Prediction With Structured Longitudinal Electronic Health Record Data
authors: Zhu Yinghao, Wang Zixiang, Gao Junyi, Tong Yuning, An Jingkun, Liao Weibin, Harrison Ewen M., Ma Liantao, Pan Chengwei
conference: "Arxiv"
year: 2024
bibkey: zhu2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01713"}
  - {name: "Code", url: "https://github.com/yhzhu99/llm4healthcare"}
tags: ['Few Shot', 'GPT', 'Has Code', 'In Context Learning', 'Merging', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
The inherent complexity of structured longitudinal Electronic Health Records (EHR) data poses a significant challenge when integrated with Large Language Models (LLMs) which are traditionally tailored for natural language processing. Motivated by the urgent need for swift decision-making during new disease outbreaks where traditional predictive models often fail due to a lack of historical data this research investigates the adaptability of LLMs like GPT-4 to EHR data. We particularly focus on their zero-shot capabilities which enable them to make predictions in scenarios in which they havent been explicitly trained. In response to the longitudinal sparse and knowledge-infused nature of EHR data our prompting approach involves taking into account specific EHR characteristics such as units and reference ranges and employing an in-context learning strategy that aligns with clinical contexts. Our comprehensive experiments on the MIMIC-IV and TJH datasets demonstrate that with our elaborately designed prompting framework LLMs can improve prediction performance in key tasks such as mortality length-of-stay and 30-day readmission by about 3537; surpassing ML models in few-shot settings. Our research underscores the potential of LLMs in enhancing clinical decision-making especially in urgent healthcare situations like the outbreak of emerging diseases with no labeled data. The code is publicly available at https://github.com/yhzhu99/llm4healthcare for reproducibility.
