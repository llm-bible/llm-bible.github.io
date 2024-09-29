---
layout: publication
title: Pushing The Limits Of Chatgpt On NLP Tasks
authors: Sun Xiaofei, Dong Linfeng, Li Xiaoya, Wan Zhen, Wang Shuhe, Zhang Tianwei, Li Jiwei, Cheng Fei, Lyu Lingjuan, Wu Fei, Wang Guoyin
conference: "Arxiv"
year: 2023
bibkey: sun2023pushing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.09719"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security']
---
Despite the success of ChatGPT its performances on most NLP tasks are still well below the supervised baselines. In this work we looked into the causes and discovered that its subpar performance was caused by the following factors (1) token limit in the prompt does not allow for the full utilization of the supervised datasets; (2) mismatch between the generation nature of ChatGPT and NLP tasks; (3) intrinsic pitfalls of LLMs models e.g. hallucination overly focus on certain keywords etc. In this work we propose a collection of general modules to address these issues in an attempt to push the limits of ChatGPT on NLP tasks. Our proposed modules include (1) a one-input-multiple-prompts strategy that employs multiple prompts for one input to accommodate more demonstrations; (2) using fine-tuned models for better demonstration retrieval; (3) transforming tasks to formats that are more tailored to the generation nature; (4) employing reasoning strategies that are tailored to addressing the task-specific complexity; (5) the self-verification strategy to address the hallucination issue of LLMs; (6) the paraphrase strategy to improve the robustness of model predictions. We conduct experiments on 21 datasets of 10 representative NLP tasks including question answering commonsense reasoning natural language inference sentiment analysis named entity recognition entity-relation extraction event extraction dependency parsing semantic role labeling and part-of-speech tagging. Using the proposed assemble of techniques we are able to significantly boost the performance of ChatGPT on the selected NLP tasks achieving performances comparable to or better than supervised baselines or even existing SOTA performances.
