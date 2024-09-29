---
layout: publication
title: Web2code A Large45;scale Webpage45;to45;code Dataset And Evaluation Framework For Multimodal Llms
authors: Yun Sukmin, Lin Haokun, Thushara Rusiru, Bhat Mohammad Qazim, Wang Yongxin, Jiang Zutao, Deng Mingkai, Wang Jinhong, Tao Tianhua, Li Junbo, Li Haonan, Nakov Preslav, Baldwin Timothy, Liu Zhengzhong, Xing Eric P., Liang Xiaodan, Shen Zhiqiang
conference: "Arxiv"
year: 2024
bibkey: yun2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20098"}
  - {name: "Code", url: "https://github.com/MBZUAI&#45;LLM/web2code"}
tags: ['Applications', 'Has Code', 'Multimodal Models', 'RAG', 'Tools']
---
Multimodal large language models (MLLMs) have shown impressive success across modalities such as image video and audio in a variety of understanding and generation tasks. However current MLLMs are surprisingly poor at understanding webpage screenshots and generating their corresponding HTML code. To address this problem we propose Web2Code a benchmark consisting of a new large45;scale webpage45;to45;code dataset for instruction tuning and an evaluation framework for the webpage understanding and HTML code translation abilities of MLLMs. For dataset construction we leverage pretrained LLMs to enhance existing webpage45;to45;code datasets as well as generate a diverse pool of new webpages rendered into images. Specifically the inputs are webpage images and instructions while the responses are the webpages HTML code. We further include diverse natural language QA pairs about the webpage content in the responses to enable a more comprehensive understanding of the web content. To evaluate model performance in these tasks we develop an evaluation framework for testing MLLMs abilities in webpage understanding and web45;to45;code generation. Extensive experiments show that our proposed dataset is beneficial not only to our proposed tasks but also in the general visual domain while previous datasets result in worse performance. We hope our work will contribute to the development of general MLLMs suitable for web45;based content generation and task automation. Our data and code will be available at https://github.com/MBZUAI&#45;LLM/web2code.
