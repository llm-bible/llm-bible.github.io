---
layout: publication
title: Large Language Models Might Not Care What You Are Saying&#58; Prompt Format Beats Descriptions
authors: Tang Chenming, Wang Zhixiang, Wu Yunfang
conference: "Arxiv"
year: 2024
bibkey: tang2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08780"}
tags: ['Applications', 'In Context Learning', 'Prompting', 'Tools']
---
With the help of in-context learning (ICL) large language models (LLMs) have achieved impressive performance across various tasks. However the function of descriptive instructions during ICL remains under-explored. In this work we propose an ensemble prompt framework to describe the selection criteria of multiple in-context examples and preliminary experiments on machine translation (MT) across six translation directions confirm that this framework boosts ICL perfromance. But to our surprise LLMs might not necessarily care what the descriptions actually say and the performance gain is primarily caused by the ensemble format since the framework could lead to improvement even with random descriptive nouns. We further apply this new ensemble prompt on a range of commonsense math logical reasoning and hallucination tasks with three LLMs and achieve promising results suggesting again that designing a proper prompt format would be much more effective and efficient than paying effort into specific descriptions. Our code will be publicly available once this paper is published.
