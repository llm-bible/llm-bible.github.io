---
layout: publication
title: DCR Divide45;and45;conquer Reasoning For Multi45;choice Question Answering With Llms
authors: Meng Zijie, Zhang Yan, Feng Zhaopeng, Liu Zuozhu
conference: "Arxiv"
year: 2024
bibkey: meng2024divide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05190"}
  - {name: "Code", url: "https://github.com/AiMijie/Divide&#45;and&#45;Conquer&#125;"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have shown impressive performance in reasoning benchmarks with the emergence of Chain45;of45;Thought (CoT) particularly in multi45;choice question (MCQ). However current works equally resolve questions regardless of the problem45;solving difficulty leading to an excessive focus on simple items while insufficient attention on intricate ones. To address this challenge we propose a simple yet effective strategy Divide and Conquer Reasoning (DCR) to enhance the reasoning capability of LLMs for MCQs as inspired by human beings using heuristics to first categorize tasks and then handle them separately. In particular we first categorize questions into two subsets based on confidence score (mathcal123;CS125;) which is estimated by statistical frequency of generated answers. Subsequently we propose Filter Choices based Reasoning (FCR) to improve model performance on MCQs with low (mathcal123;CS125;). Our experiments demonstrate that the proposed strategy only costs 8537; of SOTA while still achieves average accuracy improvement of 1.5637; across nine datasets including arithmetic commonsense and logic reasoning tasks. The code is at url123;https://github.com/AiMijie/Divide&#45;and&#45;Conquer&#125;
