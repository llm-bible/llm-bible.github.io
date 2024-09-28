---
layout: publication
title: Long-context LLMs Struggle with Long In-context Learning
authors: Li Tianle, Zhang Ge, Do Quy Duc, Yue Xiang, Chen Wenhu
conference: "Arxiv"
year: 2024
bibkey: li2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02060"}
tags: ['Arxiv', 'Ethics and Bias']
---
Large Language Models (LLMs) have made significant strides in handling long sequences. Some models like Gemini could even to be capable of dealing with millions of tokens. However their performance evaluation has largely been confined to metrics like perplexity and synthetic tasks which may not fully capture their true abilities in more challenging real-world scenarios. We introduce a benchmark (LongICLBench) for long in-context learning in extreme-label classification using six datasets with 28 to 174 classes and input lengths from 2K to 50K tokens. Our benchmark requires LLMs to comprehend the entire input to recognize the massive label spaces to make correct predictions. We evaluate on 15 long-context LLMs and find that they perform well on less challenging classification tasks with smaller label space and shorter demonstrations. However they struggle with more challenging task like Discovery with 174 labels suggesting a gap in their ability to process long context-rich sequences. Further analysis reveals a bias towards labels presented later in the sequence and a need for improved reasoning over multiple pieces of information. Our study reveals that long context understanding and reasoning is still a challenging task for the existing LLMs. We believe LongICLBench could serve as a more realistic evaluation for the future long-context LLMs.
