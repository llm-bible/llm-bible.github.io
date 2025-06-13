---
layout: publication
title: 'Web2code: A Large-scale Webpage-to-code Dataset And Evaluation Framework For Multimodal Llms'
authors: Sukmin Yun, Haokun Lin, Rusiru Thushara, Mohammad Qazim Bhat, Yongxin Wang, Zutao Jiang, Mingkai Deng, Jinhong Wang, Tianhua Tao, Junbo Li, Haonan Li, Preslav Nakov, Timothy Baldwin, Zhengzhong Liu, Eric P. Xing, Xiaodan Liang, Zhiqiang Shen
conference: "Arxiv"
year: 2024
bibkey: yun2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20098"}
  - {name: "Code", url: "https://github.com/MBZUAI-LLM/web2code"}
tags: ['RAG', 'Tools', 'Multimodal Models', 'Has Code']
---
Multimodal large language models (MLLMs) have shown impressive success across
modalities such as image, video, and audio in a variety of understanding and
generation tasks. However, current MLLMs are surprisingly poor at understanding
webpage screenshots and generating their corresponding HTML code. To address
this problem, we propose \\(\texttt\{Web2Code\}\\), a benchmark consisting of a new
large-scale webpage-to-code dataset for instruction tuning and an evaluation
framework for the webpage understanding and HTML code translation abilities of
MLLMs. For dataset construction, we leverage pretrained LLMs to enhance
existing webpage-to-code datasets as well as generate a diverse pool of new
webpages rendered into images. Specifically, the inputs are webpage images and
instructions, while the responses are the webpage's HTML code. We further
include diverse natural language QA pairs about the webpage content in the
responses to enable a more comprehensive understanding of the web content. To
evaluate model performance in these tasks, we develop an evaluation framework
for testing MLLMs' abilities in webpage understanding and web-to-code
generation. Extensive experiments show that our proposed dataset is beneficial
not only to our proposed tasks but also in the general visual domain. We hope
our work will contribute to the development of general MLLMs suitable for
web-based content generation and task automation. Our data and code are
available at https://github.com/MBZUAI-LLM/web2code.
