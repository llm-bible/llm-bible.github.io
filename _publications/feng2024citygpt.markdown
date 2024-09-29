---
layout: publication
title: CityGPT Empowering Urban Spatial Cognition of Large Language Models
authors: Feng Jie, Du Yuwei, Liu Tianhui, Guo Siqi, Lin Yuming, Li Yong
conference: "Arxiv"
year: 2024
bibkey: feng2024citygpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13948"}
  - {name: "Code", url: "https://github.com/tsinghua-fib-lab/CityGPT"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models(LLMs) with powerful language generation and reasoning capabilities have already achieved success in many domains e.g. math and code generation. However due to the lacking of physical worlds corpus and knowledge during training they usually fail to solve many real-life tasks in the urban space. In this paper we propose CityGPT a systematic framework for enhancing the capability of LLMs on understanding urban space and solving the related urban tasks by building a city-scale world model in the model. First we construct a diverse instruction tuning dataset CityInstruction for injecting urban knowledge and enhancing spatial reasoning capability effectively. By using a mixture of CityInstruction and general instruction data we fine-tune various LLMs (e.g. ChatGLM3-6B Qwen1.5 and LLama3 series) to enhance their capability without sacrificing general abilities. To further validate the effectiveness of proposed methods we construct a comprehensive benchmark CityEval to evaluate the capability of LLMs on diverse urban scenarios and problems. Extensive evaluation results demonstrate that small LLMs trained with CityInstruction can achieve competitive performance with commercial LLMs in the comprehensive evaluation of CityEval. The source codes are openly accessible to the research community via https://github.com/tsinghua-fib-lab/CityGPT.
