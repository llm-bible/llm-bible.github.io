---
layout: publication
title: Gerea Question45;aware Prompt Captions For Knowledge45;based Visual Question Answering
authors: Ma Ziyu, Li Shutao, Sun Bin, Cai Jianfei, Long Zuxiang, Ma Fuyan
conference: "Arxiv"
year: 2024
bibkey: ma2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02503"}
  - {name: "Code", url: "https://github.com/Upper9527/GeReA"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Knowledge45;based visual question answering (VQA) requires world knowledge beyond the image for accurate answer. Recently instead of extra knowledge bases a large language model (LLM) like GPT45;3 is activated as an implicit knowledge engine to jointly acquire and reason the necessary knowledge for answering by converting images into textual information (e.g. captions and answer candidates). However such conversion may introduce irrelevant information which causes the LLM to misinterpret images and ignore visual details crucial for accurate knowledge. We argue that multimodal large language model (MLLM) is a better implicit knowledge engine than the LLM for its superior capability of visual understanding. Despite this how to activate the capacity of MLLM as the implicit knowledge engine has not been explored yet. Therefore we propose GeReA a generate45;reason framework that prompts a MLLM like InstructBLIP with question relevant vision and language information to generate knowledge45;relevant descriptions and reasons those descriptions for knowledge45;based VQA. Specifically the question45;relevant image regions and question45;specific manual prompts are encoded in the MLLM to generate the knowledge relevant descriptions referred to as question45;aware prompt captions. After that the question45;aware prompt captions image45;question pair and similar samples are sent into the multi45;modal reasoning model to learn a joint knowledge45;image45;question representation for answer prediction. GeReA unlocks the use of MLLM as the implicit knowledge engine surpassing all previous state45;of45;the45;art methods on OK45;VQA and A45;OKVQA datasets with test accuracies of 66.537; and 63.337; respectively. Our code will be released at https://github.com/Upper9527/GeReA.
