---
layout: publication
title: Fennec Fine-grained Language Model Evaluation and Correction Extended through Branching and Bridging
authors: Liang Xiaobo, Zhang Haoke, Hu Helan, Li Juntao, Xu Jun, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: liang2024fennec
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12163"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The rapid advancement of large language models has given rise to a plethora of applications across a myriad of real-world tasks mainly centered on aligning with human intent. However the complexities inherent in human intent necessitate a dependence on labor-intensive and time-consuming human evaluation. To alleviate this constraint we delve into the paradigm of employing open-source large language models as evaluators aligning with the prevailing trend of utilizing GPT-4. Particularly we present a step-by-step evaluation framework capable of ine-grained valuatio and correctio xtended through branhing and bridging. Specifically the branching operation dissects the evaluation task into various dimensions and granularities thereby alleviating the challenges associated with evaluation. Concurrently the bridging operation amalgamates diverse training datasets augmenting the variety of evaluation tasks. In experimental trials our 7B model consistently outperforms open-source larger-scale evaluation models across various widely adopted benchmarks in terms of both and closely approaching the capabilities of GPT-4. We employ the fine-grained correction capabilities induced by the evaluation model to refine multiple model responses and the results show that the refinement elevates the quality of responses leading to an improvement of 1-2 points on the MT-Bench. Our code is available at Github.
