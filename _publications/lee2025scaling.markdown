---
layout: publication
title: 'SEAL: Scaling To Emphasize Attention For Long-context Retrieval'
authors: Changhun Lee, Jun-gyu Jin, Younghyun Cho, Eunhyeok Park
conference: "Arxiv"
year: 2025
bibkey: lee2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15225"}
tags: ['Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Model Architecture']
---
In this work, we introduce a novel approach called Scaling to Emphasize
Attention for Long-context retrieval (SEAL), which enhances the retrieval
performance of large language models (LLMs) over extended contexts. Previous
studies have shown that each attention head in LLMs has a unique functionality
and collectively contributes to the overall behavior of the model. Similarly,
we observe that specific heads are closely tied to long-context retrieval,
showing positive or negative correlation with retrieval scores. Built on this
insight, we propose a learning-based mechanism using zero-shot generated data
to emphasize these heads, improving the model's performance in long-context
retrieval tasks. By applying SEAL, we can achieve significant improvements in
in-domain retrieval performance, including document QA tasks from LongBench,
and considerable improvements in out-of-domain cases. Additionally, when
combined with existing training-free context extension techniques, SEAL extends
the context limits of LLMs while maintaining highly reliable outputs, opening
new avenues for research in this field.
