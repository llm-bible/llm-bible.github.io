---
layout: publication
title: Interactive Text45;to45;image Retrieval With Large Language Models A Plug45;and45;play Approach
authors: Lee Saehyung, Yu Sangwon, Park Junsung, Yi Jihun, Yoon Sungroh
conference: "Arxiv"
year: 2024
bibkey: lee2024interactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03411"}
  - {name: "Code", url: "https://github.com/Saehyung&#45;Lee/PlugIR"}
tags: ['Applications', 'Has Code']
---
In this paper we primarily address the issue of dialogue45;form context query within the interactive text45;to45;image retrieval task. Our methodology PlugIR actively utilizes the general instruction45;following capability of LLMs in two ways. First by reformulating the dialogue45;form context we eliminate the necessity of fine45;tuning a retrieval model on existing visual dialogue data thereby enabling the use of any arbitrary black45;box model. Second we construct the LLM questioner to generate non45;redundant questions about the attributes of the target image based on the information of retrieval candidate images in the current context. This approach mitigates the issues of noisiness and redundancy in the generated questions. Beyond our methodology we propose a novel evaluation metric Best log Rank Integral (BRI) for a comprehensive assessment of the interactive retrieval system. PlugIR demonstrates superior performance compared to both zero45;shot and fine45;tuned baselines in various benchmarks. Additionally the two methodologies comprising PlugIR can be flexibly applied together or separately in various situations. Our codes are available at https://github.com/Saehyung&#45;Lee/PlugIR.
