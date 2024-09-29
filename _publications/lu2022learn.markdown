---
layout: publication
title: Learn To Explain Multimodal Reasoning Via Thought Chains For Science Question Answering
authors: Lu Pan, Mishra Swaroop, Xia Tony, Qiu Liang, Chang Kai-wei, Zhu Song-chun, Tafjord Oyvind, Clark Peter, Kalyan Ashwin
conference: "Arxiv"
year: 2022
bibkey: lu2022learn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.09513"}
  - {name: "Code", url: "https://scienceqa.github.io"}
tags: ['Applications', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'RAG']
---
When answering a question humans utilize the information available across different modalities to synthesize a consistent and complete chain of thought (CoT). This process is normally a black box in the case of deep learning models like large45;scale language models. Recently science question benchmarks have been used to diagnose the multi45;hop reasoning ability and interpretability of an AI system. However existing datasets fail to provide annotations for the answers or are restricted to the textual45;only modality small scales and limited domain diversity. To this end we present Science Question Answering (ScienceQA) a new benchmark that consists of ~21k multimodal multiple choice questions with a diverse set of science topics and annotations of their answers with corresponding lectures and explanations. We further design language models to learn to generate lectures and explanations as the chain of thought (CoT) to mimic the multi45;hop reasoning process when answering ScienceQA questions. ScienceQA demonstrates the utility of CoT in language models as CoT improves the question answering performance by 1.2037; in few45;shot GPT45;3 and 3.9937; in fine45;tuned UnifiedQA. We also explore the upper bound for models to leverage explanations by feeding those in the input; we observe that it improves the few45;shot performance of GPT45;3 by 18.9637;. Our analysis further shows that language models similar to humans benefit from explanations to learn from fewer data and achieve the same performance with just 4037; of the data. The data and code are available at https://scienceqa.github.io.
