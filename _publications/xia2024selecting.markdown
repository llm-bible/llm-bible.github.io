---
layout: publication
title: LESS Selecting Influential Data For Targeted Instruction Tuning
authors: Xia Mengzhou, Malladi Sadhika, Gururangan Suchin, Arora Sanjeev, Chen Danqi
conference: "Arxiv"
year: 2024
bibkey: xia2024selecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04333"}
tags: ['Applications', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Instruction tuning has unlocked powerful capabilities in large language models (LLMs) effectively using combined datasets to develop generalpurpose chatbots. However real45;world applications often require a specialized suite of skills (e.g. reasoning). The challenge lies in identifying the most relevant data from these extensive datasets to effectively develop specific capabilities a setting we frame as targeted instruction tuning. We propose LESS an optimizer45;aware and practically efficient algorithm to effectively estimate data influences and perform Low45;rank gradiEnt Similarity Search for instruction data selection. Crucially LESS adapts existing influence formulations to work with the Adam optimizer and variable45;length instruction data. LESS first constructs a highly reusable and transferable gradient datastore with low45;dimensional gradient features and then selects examples based on their similarity to few45;shot examples embodying a specific capability. Experiments show that training on a LESS45;selected 537; of the data can often outperform training on the full dataset across diverse downstream tasks. Furthermore the selected data is highly transferable smaller models can be leveraged to select useful data for larger models and models from different families. Our qualitative analysis shows that our method goes beyond surface form cues to identify data that exemplifies the necessary reasoning skills for the intended downstream application.
