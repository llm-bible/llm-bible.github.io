---
layout: publication
title: 'Easyedit2: An Easy-to-use Steering Framework For Editing Large Language Models'
authors: Ziwen Xu, Shuxun Wang, Kewei Xu, Haoming Xu, Mengru Wang, Xinle Deng, Yunzhi Yao, Guozhou Zheng, Huajun Chen, Ningyu Zhang
conference: "Arxiv"
year: 2025
bibkey: xu2025easy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15133"}
  - {name: "Code", url: "https://github.com/zjunlp/EasyEdit"}
  - {name: "Code", url: "https://zjunlp.github.io/project/EasyEdit2/video"}
tags: ['Responsible AI', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Has Code']
---
In this paper, we introduce EasyEdit2, a framework designed to enable
plug-and-play adjustability for controlling Large Language Model (LLM)
behaviors. EasyEdit2 supports a wide range of test-time interventions,
including safety, sentiment, personality, reasoning patterns, factuality, and
language features. Unlike its predecessor, EasyEdit2 features a new
architecture specifically designed for seamless model steering. It comprises
key modules such as the steering vector generator and the steering vector
applier, which enable automatic generation and application of steering vectors
to influence the model's behavior without modifying its parameters. One of the
main advantages of EasyEdit2 is its ease of use-users do not need extensive
technical knowledge. With just a single example, they can effectively guide and
adjust the model's responses, making precise control both accessible and
efficient. Empirically, we report model steering performance across different
LLMs, demonstrating the effectiveness of these techniques. We have released the
source code on GitHub at https://github.com/zjunlp/EasyEdit along with a
demonstration notebook. In addition, we provide a demo video at
https://zjunlp.github.io/project/EasyEdit2/video for a quick introduction.
