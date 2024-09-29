---
layout: publication
title: Evaluating Large Language Models on Spatial Tasks A Multi-Task Benchmarking Study
authors: Xu Liuchang, Zhao Shuo, Lin Qingming, Chen Luyao, Luo Qianqian, Wu Sensen, Ye Xinyue, Feng Hailin, Du Zhenhong
conference: "Arxiv"
year: 2024
bibkey: xu2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14438"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
The advent of large language models such as ChatGPT Gemini and others has underscored the importance of evaluating their diverse capabilities ranging from natural language understanding to code generation. However their performance on spatial tasks has not been comprehensively assessed. This study addresses this gap by introducing a novel multi-task spatial evaluation dataset designed to systematically explore and compare the performance of several advanced models on spatial tasks. The dataset encompasses twelve distinct task types including spatial understanding and path planning each with verified accurate answers. We evaluated multiple models including OpenAIs gpt-3.5-turbo gpt-4o and ZhipuAIs glm-4 through a two-phase testing approach. Initially we conducted zero-shot testing followed by categorizing the dataset by difficulty and performing prompt tuning tests. Results indicate that gpt-4o achieved the highest overall accuracy in the first phase with an average of 71.3. Although moonshot-v1-8k slightly underperformed overall it surpassed gpt-4o in place name recognition tasks. The study also highlights the impact of prompt strategies on model performance in specific tasks. For example the Chain-of-Thought (COT) strategy increased gpt-4os accuracy in path planning from 12.4 to 87.5 while a one-shot strategy enhanced moonshot-v1-8ks accuracy in mapping tasks from 10.1 to 76.3.
