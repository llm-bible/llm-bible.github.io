---
layout: publication
title: What Are The Essential Factors In Crafting Effective Long Context Multi45;hop Instruction Datasets Insights And Best Practices
authors: Chen Zhi, Chen Qiguang, Qin Libo, Guo Qipeng, Lv Haijun, Zou Yicheng, Che Wanxiang, Yan Hang, Chen Kai, Lin Dahua
conference: "Arxiv"
year: 2024
bibkey: chen2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01893"}
  - {name: "Code", url: "https://github.com/WowCZ/LongMIT"}
tags: ['Agentic', 'Applications', 'Has Code', 'Merging', 'Tools']
---
Recent advancements in large language models (LLMs) with extended context windows have significantly improved tasks such as information extraction question answering and complex planning scenarios. In order to achieve success in long context tasks a large amount of work has been done to enhance the long context capabilities of the model through synthetic data. Existing methods typically utilize the Self45;Instruct framework to generate instruction tuning data for better long context capability improvement. However our preliminary experiments indicate that less than 3537; of generated samples are multi45;hop and more than 4037; exhibit poor quality limiting comprehensive understanding and further research. To improve the quality of synthetic data we propose the Multi45;agent Interactive Multi45;hop Generation (MIMG) framework incorporating a Quality Verification Agent a Single45;hop Question Generation Agent a Multiple Question Sampling Strategy and a Multi45;hop Question Merger Agent. This framework improves the data quality with the proportion of high45;quality multi45;hop and diverse data exceeding 8537;. Furthermore we systematically investigate strategies for document selection question merging and validation techniques through extensive experiments across various models. Our findings show that our synthetic high45;quality long45;context instruction data significantly enhances model performance even surpassing models trained on larger amounts of human45;annotated data. Our code is available at https://github.com/WowCZ/LongMIT.
