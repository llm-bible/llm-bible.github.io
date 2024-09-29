---
layout: publication
title: AIM Let Any Multi45;modal Large Language Models Embrace Efficient In45;context Learning
authors: Gao Jun, Qiao Qian, Cao Ziqiang, Wang Zili, Li Wenjie
conference: "Arxiv"
year: 2024
bibkey: gao2024let
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07588"}
tags: ['Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Tools']
---
In45;context learning (ICL) facilitates Large Language Models (LLMs) exhibiting emergent ability on downstream tasks without updating billions of parameters. However in the area of multi45;modal Large Language Models (MLLMs) two problems hinder the application of multi45;modal ICL (1) Most primary MLLMs are only trained on single45;image datasets making them unable to read multi45;modal demonstrations. (2) With the demonstrations increasing thousands of visual tokens highly challenge hardware and degrade ICL performance. During preliminary explorations we discovered that the inner LLM tends to focus more on the linguistic modality within multi45;modal demonstrations to generate responses. Therefore we propose a general and light45;weighted framework textbf123;AIM125; to tackle the mentioned problems through textbf123;A125;ggregating textbf123;I125;mage information of textbf123;M125;ultimodal demonstrations to the dense latent space of the corresponding linguistic part. Specifically AIM first uses the frozen backbone MLLM to read each image45;text demonstration and extracts the vector representations on top of the text. These vectors naturally fuse the information of the image45;text pair and AIM transforms them into fused virtual tokens acceptable for the inner LLM via a trainable projection layer. Ultimately these fused tokens function as variants of multi45;modal demonstrations fed into the MLLM to direct its response to the current query as usual. Because these fused tokens stem from the textual component of the image45;text pair a multi45;modal demonstration is nearly reduced to a pure textual demonstration thus seamlessly applying to any MLLMs. With its de facto MLLM frozen AIM is parameter45;efficient and we train it on public multi45;modal web corpora which have nothing to do with downstream test tasks.
