---
layout: publication
title: 'Streaming Video Question-answering With In-context Video Kv-cache Retrieval'
authors: Shangzhe Di, Zhelun Yu, Guanghao Zhang, Haoyuan Li, Tao Zhong, Hao Cheng, Bolin Li, Wanggui He, Fangxun Shu, Hao Jiang
conference: "Arxiv"
year: 2025
bibkey: di2025streaming
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00540'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Applications', 'Prompting']
---
We propose ReKV, a novel training-free approach that enables efficient
streaming video question-answering (StreamingVQA), by seamlessly integrating
with existing Video Large Language Models (Video-LLMs). Traditional VideoQA
systems struggle with long videos, as they must process entire videos before
responding to queries, and repeat this process for each new question. In
contrast, our approach analyzes long videos in a streaming manner, allowing for
prompt responses as soon as user queries are received. Building on a common
Video-LLM, we first incorporate a sliding-window attention mechanism, ensuring
that input frames attend to a limited number of preceding frames, thereby
reducing computational overhead. To prevent information loss, we store
processed video key-value caches (KV-Caches) in RAM and disk, reloading them
into GPU memory as needed. Additionally, we introduce a retrieval method that
leverages an external retriever or the parameters within Video-LLMs to retrieve
only query-relevant KV-Caches, ensuring both efficiency and accuracy in
question answering. ReKV enables the separation of video encoding and
question-answering across different processes and GPUs, significantly enhancing
the efficiency of StreamingVQA. Through comprehensive experimentation, we
validate the efficacy and practicality of our approach, which significantly
boosts efficiency and enhances applicability over existing VideoQA models.
