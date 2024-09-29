---
layout: publication
title: Analyzing And Adapting Large Language Models For Few45;shot Multilingual NLU Are We There Yet
authors: Razumovskaia Evgeniia, Vulić Ivan, Korhonen Anna
conference: "Arxiv"
year: 2024
bibkey: razumovskaia2024analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01929"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Prompting']
---
Supervised fine45;tuning (SFT) supervised instruction tuning (SIT) and in45;context learning (ICL) are three alternative de facto standard approaches to few45;shot learning. ICL has gained popularity recently with the advent of LLMs due to its simplicity and sample efficiency. Prior research has conducted only limited investigation into how these approaches work for multilingual few45;shot learning and the focus so far has been mostly on their performance. In this work we present an extensive and systematic comparison of the three approaches testing them on 6 high45; and low45;resource languages three different NLU tasks and a myriad of language and domain setups. Importantly performance is only one aspect of the comparison where we also analyse the approaches through the optics of their computational inference and financial costs. Our observations show that supervised instruction tuning has the best trade45;off between performance and resource requirements. As another contribution we analyse the impact of target language adaptation of pretrained LLMs and find that the standard adaptation approaches can (superficially) improve target language generation capabilities but language understanding elicited through ICL does not improve and remains limited with low scores especially for low45;resource languages.
