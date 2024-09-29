---
layout: publication
title: Large Language Models Leverage External Knowledge to Extend Clinical Insight Beyond Language Boundaries
authors: Wu Jiageng, Wu Xian, Qiu Zhaopeng, Li Minghui, Zhang Yingying, Zheng Yefeng, Yuan Changzheng, Yang Jie
conference: "Arxiv"
year: 2023
bibkey: wu2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10163"}
tags: ['Applications', 'Few Shot', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
textbfObjectives Large Language Models (LLMs) such as ChatGPT and Med-PaLM have excelled in various medical question-answering tasks. However these English-centric models encounter challenges in non-English clinical settings primarily due to limited clinical knowledge in respective languages a consequence of imbalanced training corpora. We systematically evaluate LLMs in the Chinese medical context and develop a novel in-context learning framework to enhance their performance. textbfMaterials and Methods The latest China National Medical Licensing Examination (CNMLE-2022) served as the benchmark. We collected 53 medical books and 381149 medical questions to construct the medical knowledge base and question bank. The proposed Knowledge and Few-shot Enhancement In-context Learning (KFE) framework leverages the in-context learning ability of LLMs to integrate diverse external clinical knowledge sources. We evaluated KFE with ChatGPT(GPT3.5) GPT4 Baichuan2(BC2)-7B and BC2-13B in CNMLE-2022 and investigated the effectiveness of different pathways for incorporating LLMs with medical knowledge from 7 perspectives. textbfResults Directly applying ChatGPT failed to qualify for the CNMLE-2022 at a score of 51. Cooperated with the KFE the LLMs with varying sizes yielded consistent and significant improvements. The ChatGPTs performance surged to 70.04 and GPT-4 achieved the highest score of 82.59. This surpasses the qualification threshold (60) and exceeds the average human score of 68.70. It also enabled a smaller BC2-13B to pass the examination showcasing the great potential in low-resource settings. textbfConclusion By synergizing medical knowledge through in-context learning LLM can extend clinical insight beyond language barriers significantly reducing language-related disparities of LLM applications and ensuring global benefit in healthcare.
