---
layout: publication
title: Hint-enhanced In-context Learning Wakes Large Language Models Up For Knowledge-intensive Tasks
authors: Wang Yifan, Guo Qingyan, Ni Xinzhe, Shi Chufan, Liu Lemao, Jiang Haiyun, Yang Yujiu
conference: "Arxiv"
year: 2023
bibkey: wang2023hint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01949"}
tags: ['Applications', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG']
---
In-context learning (ICL) ability has emerged with the increasing scale of large language models (LLMs) enabling them to learn input-label mappings from demonstrations and perform well on downstream tasks. However under the standard ICL setting LLMs may sometimes neglect query-related information in demonstrations leading to incorrect predictions. To address this limitation we propose a new paradigm called Hint-enhanced In-Context Learning (HICL) to explore the power of ICL in open-domain question answering an important form in knowledge-intensive tasks. HICL leverages LLMs reasoning ability to extract query-related knowledge from demonstrations then concatenates the knowledge to prompt LLMs in a more explicit way. Furthermore we track the source of this knowledge to identify specific examples and introduce a Hint-related Example Retriever (HER) to select informative examples for enhanced demonstrations. We evaluate HICL with HER on 3 open-domain QA benchmarks and observe average performance gains of 2.89 EM score and 2.52 F1 score on gpt-3.5-turbo 7.62 EM score and 7.27 F1 score on LLaMA-2-Chat-7B compared with standard setting.
