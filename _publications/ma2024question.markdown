---
layout: publication
title: 'Gerea: Question-aware Prompt Captions For Knowledge-based Visual Question Answering'
authors: Ma Ziyu, Li Shutao, Sun Bin, Cai Jianfei, Long Zuxiang, Ma Fuyan
conference: "Arxiv"
year: 2024
bibkey: ma2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02503"}
  - {name: "Code", url: "https://github.com/Upper9527/GeReA"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Knowledge-based visual question answering (VQA) requires world knowledge beyond the image for accurate answer. Recently, instead of extra knowledge bases, a large language model (LLM) like GPT-3 is activated as an implicit knowledge engine to jointly acquire and reason the necessary knowledge for answering by converting images into textual information (e.g., captions and answer candidates). However, such conversion may introduce irrelevant information, which causes the LLM to misinterpret images and ignore visual details crucial for accurate knowledge. We argue that multimodal large language model (MLLM) is a better implicit knowledge engine than the LLM for its superior capability of visual understanding. Despite this, how to activate the capacity of MLLM as the implicit knowledge engine has not been explored yet. Therefore, we propose GeReA, a generate-reason framework that prompts a MLLM like InstructBLIP with question relevant vision and language information to generate knowledge-relevant descriptions and reasons those descriptions for knowledge-based VQA. Specifically, the question-relevant image regions and question-specific manual prompts are encoded in the MLLM to generate the knowledge relevant descriptions, referred to as question-aware prompt captions. After that, the question-aware prompt captions, image-question pair, and similar samples are sent into the multi-modal reasoning model to learn a joint knowledge-image-question representation for answer prediction. GeReA unlocks the use of MLLM as the implicit knowledge engine, surpassing all previous state-of-the-art methods on OK-VQA and A-OKVQA datasets, with test accuracies of 66.5&#37; and 63.3&#37; respectively. Our code will be released at https://github.com/Upper9527/GeReA.
