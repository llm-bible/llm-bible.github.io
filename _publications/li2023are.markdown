---
layout: publication
title: Are Human45;generated Demonstrations Necessary For In45;context Learning
authors: Li Rui, Wang Guoyin, Li Jiwei
conference: "Arxiv"
year: 2023
bibkey: li2023are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.14681"}
  - {name: "Code", url: "https://github.com/ruili33/SEC"}
tags: ['Applications', 'Has Code', 'Prompting', 'Tools', 'Training Techniques']
---
Despite the promising few45;shot ability of large language models (LLMs) the standard paradigm of In45;context Learning (ICL) suffers the disadvantages of susceptibility to selected demonstrations and the intricacy to generate these demonstrations. In this paper we raise the fundamental question that whether human45;generated demonstrations are necessary for ICL. To answer this question we propose self45;contemplation prompting strategy (SEC) a paradigm free from human45;crafted demonstrations. The key point of SEC is that instead of using hand45;crafted examples as demonstrations in ICL SEC asks LLMs to first create demonstrations on their own based on which the final output is generated. SEC is a flexible framework and can be adapted to both the vanilla ICL and the chain45;of45;thought (CoT) but with greater ease as the manual45;generation process of both examples and rationale can be saved. Extensive experiments in arithmetic reasoning commonsense reasoning multi45;task language understanding and code generation benchmarks show that SEC which does not require hand45;crafted demonstrations significantly outperforms the zero45;shot learning strategy and achieves comparable results to ICL with hand45;crafted demonstrations. This demonstrates that for many tasks contemporary LLMs possess a sufficient level of competence to exclusively depend on their own capacity for decision making removing the need for external training data. Code is available at https://github.com/ruili33/SEC.
