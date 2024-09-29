---
layout: publication
title: Multi45;task Inference Can Large Language Models Follow Multiple Instructions At Once
authors: Son Guijin, Baek Sangwon, Nam Sangdae, Jeong Ilgyun, Kim Seungone
conference: "Arxiv"
year: 2024
bibkey: son2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11597"}
  - {name: "Code", url: "https://github.com/guijinSON/MTI&#45;Bench"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
Large language models (LLMs) are typically prompted to follow a single instruction per inference call. In this work we analyze whether LLMs also hold the capability to handle multiple instructions simultaneously denoted as Multi45;Task Inference. For this purpose we introduce the MTI Bench(Multi45;Task Inference Benchmark) a comprehensive evaluation benchmark encompassing 5000 instances across 25 tasks. Each task in the MTI Bench involves 2 to 3 sub45;tasks. As expected we first demonstrate that Multi45;Task Inference reduces the total inference time by 1.46 times in average since it does not require multiple inference calls. Interestingly contrary to the expectation that LLMs would perform better when tasks are divided we find that state45;of45;the45;art LLMs such as Llama45;245;Chat45;70B and GPT45;4 show up to 7.337; and 12.437; improved performance with Multi45;Task Inference compared to Single45;Task Inference on the MTI Bench. We release the MTI Bench dataset and our code at this link https://github.com/guijinSON/MTI&#45;Bench.
