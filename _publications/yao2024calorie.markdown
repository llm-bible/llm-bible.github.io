---
layout: publication
title: 'Caloraify: Calorie Estimation With Visual-text Pairing And Lora-driven Visual Language Models'
authors: Dongyu Yao, Keling Yao, Junhong Zhou, Yinghao Zhang
conference: "Arxiv"
year: 2024
bibkey: yao2024calorie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09936"}
  - {name: "Code", url: "https://github.com/KennyYao2001/16824-CaLORAify"}
tags: ['Agentic', 'Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Has Code']
---
The obesity phenomenon, known as the heavy issue, is a leading cause of
preventable chronic diseases worldwide. Traditional calorie estimation tools
often rely on specific data formats or complex pipelines, limiting their
practicality in real-world scenarios. Recently, vision-language models (VLMs)
have excelled in understanding real-world contexts and enabling conversational
interactions, making them ideal for downstream tasks such as ingredient
analysis. However, applying VLMs to calorie estimation requires domain-specific
data and alignment strategies. To this end, we curated CalData, a 330K
image-text pair dataset tailored for ingredient recognition and calorie
estimation, combining a large-scale recipe dataset with detailed nutritional
instructions for robust vision-language training. Built upon this dataset, we
present CaLoRAify, a novel VLM framework aligning ingredient recognition and
calorie estimation via training with visual-text pairs. During inference, users
only need a single monocular food image to estimate calories while retaining
the flexibility of agent-based conversational interaction. With Low-rank
Adaptation (LoRA) and Retrieve-augmented Generation (RAG) techniques, our
system enhances the performance of foundational VLMs in the vertical domain of
calorie estimation. Our code and data are fully open-sourced at
https://github.com/KennyYao2001/16824-CaLORAify.
