---
layout: publication
title: Culturax A Cleaned Enormous And Multilingual Dataset For Large Language Models In 167 Languages
authors: Nguyen Thuat, Van Nguyen Chien, Lai Viet Dac, Man Hieu, Ngo Nghia Trung, Dernoncourt Franck, Rossi Ryan A., Nguyen Thien Huu
conference: "Arxiv"
year: 2023
bibkey: nguyen2023multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.09400"}
tags: ['Applications', 'Ethics And Bias', 'Reinforcement Learning', 'Training Techniques']
---
The driving factors behind the development of large language models (LLMs) with impressive learning capabilities are their colossal model sizes and extensive training datasets. Along with the progress in natural language processing LLMs have been frequently made accessible to the public to foster deeper investigation and applications. However when it comes to training datasets for these LLMs especially the recent state-of-the-art models they are often not fully disclosed. Creating training data for high-performing LLMs involves extensive cleaning and deduplication to ensure the necessary level of quality. The lack of transparency for training data has thus hampered research on attributing and addressing hallucination and bias issues in LLMs hindering replication efforts and further advancements in the community. These challenges become even more pronounced in multilingual learning scenarios where the available multilingual text datasets are often inadequately collected and cleaned. Consequently there is a lack of open-source and readily usable dataset to effectively train LLMs in multiple languages. To overcome this issue we present CulturaX a substantial multilingual dataset with 6.3 trillion tokens in 167 languages tailored for LLM development. Our dataset undergoes meticulous cleaning and deduplication through a rigorous pipeline of multiple stages to accomplish the best quality for model training including language identification URL-based filtering metric-based cleaning document refinement and data deduplication. CulturaX is fully released to the public in HuggingFace to facilitate research and advancements in multilingual LLMs https://huggingface.co/datasets/uonlp/CulturaX.
