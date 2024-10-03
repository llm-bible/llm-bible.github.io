---
layout: publication
title: 'Freeva: Offline MLLM As Training-free Video Assistant'
authors: Wu Wenhao
conference: "Arxiv"
year: 2024
bibkey: wu2024offline
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07798"}
  - {name: "Code", url: "https://github.com/whwu95/FreeVA"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Tools', 'Training Techniques']
---
This paper undertakes an empirical study to revisit the latest advancements in Multimodal Large Language Models (MLLMs): Video Assistant. This study, namely FreeVA, aims to extend existing image-based MLLM to the video domain in a training-free manner. The study provides an essential, yet must-know baseline, and reveals several surprising findings: 1) FreeVA, leveraging only offline image-based MLLM without additional training, excels in zero-shot video question-answering (e.g., MSVD-QA, ActivityNet-QA, and MSRVTT-QA), even surpassing state-of-the-art methods that involve video instruction tuning. 2) While mainstream video-based MLLMs typically initialize with an image-based MLLM (e.g., LLaVA) and then fine-tune using video instruction tuning, the study indicates that utilizing the widely adopted VideoInstruct-100K for video instruction tuning doesn't actually lead to better performance compared to not training at all. 3) The commonly used evaluation metrics in existing works are significantly influenced by changes in the GPT API version over time. If ignored, this could affect the fairness and uniformity of comparisons between different methods and impact the analysis and judgment of researchers in the field. The advancement of MLLMs is currently thriving, drawing numerous researchers into the field. We aim for this work to serve as a plug-and-play, simple yet effective baseline, encouraging the direct evaluation of existing MLLMs in video domain while also standardizing the field of video conversational models to a certain extent. Also, we encourage researchers to reconsider: Have current video MLLM methods truly acquired knowledge beyond image MLLM? Code is available at https://github.com/whwu95/FreeVA
