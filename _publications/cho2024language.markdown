---
layout: publication
title: Language45;image Models With 3D Understanding
authors: Cho Jang Hyun, Ivanovic Boris, Cao Yulong, Schmerling Edward, Wang Yue, Weng Xinshuo, Li Boyi, You Yurong, Krähenbühl Philipp, Wang Yan, Pavone Marco
conference: "Arxiv"
year: 2024
bibkey: cho2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03685"}
tags: ['Applications', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Multi45;modal large language models (MLLMs) have shown incredible capabilities in a variety of 2D vision and language tasks. We extend MLLMs perceptual capabilities to ground and reason about images in 345;dimensional space. To that end we first develop a large45;scale pre45;training dataset for 2D and 3D called LV3D by combining multiple existing 2D and 3D recognition datasets under a common task formulation as multi45;turn question45;answering. Next we introduce a new MLLM named Cube45;LLM and pre45;train it on LV3D. We show that pure data scaling makes a strong 3D perception capability without 3D specific architectural design or training objective. Cube45;LLM exhibits intriguing properties similar to LLMs (1) Cube45;LLM can apply chain45;of45;thought prompting to improve 3D understanding from 2D context information. (2) Cube45;LLM can follow complex and diverse instructions and adapt to versatile input and output formats. (3) Cube45;LLM can be visually prompted such as 2D box or a set of candidate 3D boxes from specialists. Our experiments on outdoor benchmarks demonstrate that Cube45;LLM significantly outperforms existing baselines by 21.3 points of AP45;BEV on the Talk2Car dataset for 3D grounded reasoning and 17.7 points on the DriveLM dataset for complex reasoning about driving scenarios respectively. Cube45;LLM also shows competitive results in general MLLM benchmarks such as refCOCO for 2D grounding with (87.0) average score as well as visual question answering benchmarks such as VQAv2 GQA SQA POPE etc. for complex reasoning. Our project is available at https://janghyuncho.github.io/Cube&#45;LLM.
