---
layout: publication
title: 'Citygpt: Empowering Urban Spatial Cognition Of Large Language Models'
authors: Jie Feng, Tianhui Liu, Yuwei Du, Siqi Guo, Yuming Lin, Yong Li
conference: "Arxiv"
year: 2024
bibkey: feng2024empowering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13948'}
tags: ['GPT', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Model Architecture', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models(LLMs), with their powerful language generation and reasoning capabilities, have already achieved notable success in many domains, e.g., math and code generation. However, they often fall short when tackling real-life geospatial tasks within urban environments. This limitation stems from a lack of physical world knowledge and relevant data during training. To address this gap, we propose \textit\{CityGPT\}, a systematic framework designed to enhance LLMs' understanding of urban space and improve their ability to solve the related urban tasks by integrating a city-scale `world model' into the model. Firstly, we construct a diverse instruction tuning dataset, \textit\{CityInstruction\}, for injecting urban knowledge into LLMs and effectively boosting their spatial reasoning capabilities. Using a combination of \textit\{CityInstruction\} and open source general instruction data, we introduce a novel and easy-to-use self-weighted fine-tuning method (\textit\{SWFT\}) to train various LLMs (including ChatGLM3-6B, Llama3-8B, and Qwen2.5-7B) to enhance their urban spatial capabilities without compromising, or even improving, their general abilities. Finally, to validate the effectiveness of our proposed framework, we develop a comprehensive text-based spatial benchmark \textit\{CityEval\} for evaluating the performance of LLMs across a wide range of urban scenarios and geospatial tasks. Extensive evaluation results demonstrate that smaller LLMs trained with \textit\{CityInstruction\} by \textit\{SWFT\} method can achieve performance that is competitive with, and in some cases superior to, proprietary LLMs when assessed using \textit\{CityEval\}.
