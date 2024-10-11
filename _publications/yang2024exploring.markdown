---
layout: publication
title: 'Exploring And Unleashing The Power Of Large Language Models In Automated Code Translation'
authors: Yang Zhen, Liu Fang, Yu Zhongxing, Keung Jacky Wai, Li Jia, Liu Shuo, Hong Yifan, Ma Xiaoxue, Jin Zhi, Li Ge
conference: "Arxiv"
year: 2024
bibkey: yang2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14646"}
tags: ['Prompting', 'Tools', 'Training Techniques', 'Uncategorized']
---
Code translation tools (transpilers) are developed for automatic source-to-source translation. Although learning-based transpilers have shown impressive enhancement against rule-based counterparts, owing to their task-specific pre-training on extensive monolingual corpora. Their current performance still remains unsatisfactory for practical deployment, and the associated training resources are also prohibitively expensive. LLMs pre-trained on huge amounts of human-written code/text have shown remarkable performance in many code intelligence tasks due to their powerful generality, even without task-specific training. Thus, LLMs can potentially circumvent the above limitations, but they have not been exhaustively explored yet. This paper investigates diverse LLMs and learning-based transpilers for automated code translation tasks, finding that: although certain LLMs have outperformed current transpilers, they still have some accuracy issues, where most of the failures are induced by a lack of comprehension of source programs, missing clear instructions on I/O types in translation, and ignoring discrepancies between source and target programs. Enlightened by the above findings, we further propose UniTrans, a Unified code Translation framework, applicable to various LLMs, for unleashing their power in this field. Specifically, UniTrans first crafts a series of test cases for target programs with the assistance of source programs. Next, it harnesses the above auto-generated test cases to augment the code translation and then evaluate their correctness via execution. Afterward, UniTrans further (iteratively) repairs incorrectly translated programs prompted by test case execution results. Extensive experiments are conducted on six settings of translation datasets between Python, Java, and C++. Three recent LLMs of diverse sizes are tested with UniTrans, and all achieve substantial improvements.
