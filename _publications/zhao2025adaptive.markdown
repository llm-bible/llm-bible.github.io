---
layout: publication
title: 'T\(^2\): An Adaptive Test-time Scaling Strategy For Contextual Question Answering'
authors: Zhengyi Zhao, Shubo Zhang, Zezhong Wang, Huimin Wang, Yutian Zhao, Bin Liang, Yefeng Zheng, Binyang Li, Kam-fai Wong, Xian Wu
conference: "Arxiv"
year: 2025
bibkey: zhao2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17427"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Applications']
---
Recent advances in Large Language Models (LLMs) have demonstrated remarkable performance in Contextual Question Answering (CQA). However, prior approaches typically employ elaborate reasoning strategies regardless of question complexity, leading to low adaptability. Recent efficient test-time scaling methods introduce budget constraints or early stop mechanisms to avoid overthinking for straightforward questions. But they add human bias to the reasoning process and fail to leverage models' inherent reasoning capabilities. To address these limitations, we present T\\(^2\\): Think-to-Think, a novel framework that dynamically adapts reasoning depth based on question complexity. T\\(^2\\) leverages the insight that if an LLM can effectively solve similar questions using specific reasoning strategies, it can apply the same strategy to the original question. This insight enables to adoption of concise reasoning for straightforward questions while maintaining detailed analysis for complex problems. T\\(^2\\) works through four key steps: decomposing questions into structural elements, generating similar examples with candidate reasoning strategies, evaluating these strategies against multiple criteria, and applying the most appropriate strategy to the original question. Experimental evaluation across seven diverse CQA benchmarks demonstrates that T\\(^2\\) not only achieves higher accuracy than baseline methods but also reduces computational overhead by up to 25.2%.
