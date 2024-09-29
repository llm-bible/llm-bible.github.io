---
layout: publication
title: Hint45;enhanced In45;context Learning Wakes Large Language Models Up For Knowledge45;intensive Tasks
authors: Wang Yifan, Guo Qingyan, Ni Xinzhe, Shi Chufan, Liu Lemao, Jiang Haiyun, Yang Yujiu
conference: "Arxiv"
year: 2023
bibkey: wang2023hint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01949"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
In45;context learning (ICL) ability has emerged with the increasing scale of large language models (LLMs) enabling them to learn input45;label mappings from demonstrations and perform well on downstream tasks. However under the standard ICL setting LLMs may sometimes neglect query45;related information in demonstrations leading to incorrect predictions. To address this limitation we propose a new paradigm called Hint45;enhanced In45;Context Learning (HICL) to explore the power of ICL in open45;domain question answering an important form in knowledge45;intensive tasks. HICL leverages LLMs reasoning ability to extract query45;related knowledge from demonstrations then concatenates the knowledge to prompt LLMs in a more explicit way. Furthermore we track the source of this knowledge to identify specific examples and introduce a Hint45;related Example Retriever (HER) to select informative examples for enhanced demonstrations. We evaluate HICL with HER on 3 open45;domain QA benchmarks and observe average performance gains of 2.89 EM score and 2.52 F1 score on gpt45;3.545;turbo 7.62 EM score and 7.27 F1 score on LLaMA45;245;Chat45;7B compared with standard setting.
