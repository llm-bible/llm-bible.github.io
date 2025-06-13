---
layout: publication
title: 'Chartcoder: Advancing Multimodal Large Language Model For Chart-to-code Generation'
authors: Xuanle Zhao, Xianzhen Luo, Qi Shi, Chi Chen, Shuo Wang, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: zhao2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06598"}
  - {name: "Code", url: "https://github.com/thunlp/ChartCoder"}
tags: ['Applications', 'RAG', 'Training Techniques', 'Has Code', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in chart understanding tasks. However, interpreting charts with textual descriptions often leads to information loss, as it fails to fully capture the dense information embedded in charts. In contrast, parsing charts into code provides lossless representations that can effectively contain all critical details. Although existing open-source MLLMs have achieved success in chart understanding tasks, they still face two major challenges when applied to chart-to-code tasks: (1) Low executability and poor restoration of chart details in the generated code and (2) Lack of large-scale and diverse training data. To address these challenges, we propose \textbf\{ChartCoder\}, the first dedicated chart-to-code MLLM, which leverages Code LLMs as the language backbone to enhance the executability of the generated code. Furthermore, we introduce \textbf\{Chart2Code-160k\}, the first large-scale and diverse dataset for chart-to-code generation, and propose the \textbf\{Snippet-of-Thought (SoT)\} method, which transforms direct chart-to-code generation data into step-by-step generation. Experiments demonstrate that ChartCoder, with only 7B parameters, surpasses existing open-source MLLMs on chart-to-code benchmarks, achieving superior chart restoration and code excitability. Our code is available at https://github.com/thunlp/ChartCoder.
