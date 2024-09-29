---
layout: publication
title: Freeva Offline MLLM As Training45;free Video Assistant
authors: Wu Wenhao
conference: "Arxiv"
year: 2024
bibkey: wu2024offline
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07798"}
  - {name: "Code", url: "https://github.com/whwu95/FreeVA"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Tools', 'Training Techniques']
---
This paper undertakes an empirical study to revisit the latest advancements in Multimodal Large Language Models (MLLMs) Video Assistant. This study namely FreeVA aims to extend existing image45;based MLLM to the video domain in a training45;free manner. The study provides an essential yet must45;know baseline and reveals several surprising findings 1) FreeVA leveraging only offline image45;based MLLM without additional training excels in zero45;shot video question45;answering (e.g. MSVD45;QA ActivityNet45;QA and MSRVTT45;QA) even surpassing state45;of45;the45;art methods that involve video instruction tuning. 2) While mainstream video45;based MLLMs typically initialize with an image45;based MLLM (e.g. LLaVA) and then fine45;tune using video instruction tuning the study indicates that utilizing the widely adopted VideoInstruct45;100K for video instruction tuning doesnt actually lead to better performance compared to not training at all. 3) The commonly used evaluation metrics in existing works are significantly influenced by changes in the GPT API version over time. If ignored this could affect the fairness and uniformity of comparisons between different methods and impact the analysis and judgment of researchers in the field. The advancement of MLLMs is currently thriving drawing numerous researchers into the field. We aim for this work to serve as a plug45;and45;play simple yet effective baseline encouraging the direct evaluation of existing MLLMs in video domain while also standardizing the field of video conversational models to a certain extent. Also we encourage researchers to reconsider Have current video MLLM methods truly acquired knowledge beyond image MLLM Code is available at https://github.com/whwu95/FreeVA
