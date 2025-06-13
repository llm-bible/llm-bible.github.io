---
layout: publication
title: 'Learning LLM Preference Over Intra-dialogue Pairs: A Framework For Utterance-level Understandings'
authors: Xuanqing Liu, Luyang Kong, Wei Niu, Afshin Khashei, Belinda Zeng, Steve Johnson, Jon Jay, Davor Golac, Matt Pope
conference: "Arxiv"
year: 2025
bibkey: liu2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05620"}
tags: ['Fine-Tuning', 'Training Techniques', 'Tools', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
handling complex dialogue tasks without requiring use case-specific
fine-tuning. However, analyzing live dialogues in real-time necessitates
low-latency processing systems, making it impractical to deploy models with
billions of parameters due to latency constraints. As a result, practitioners
often prefer smaller models with millions of parameters, trained on
high-quality, human-annotated datasets. Yet, curating such datasets is both
time-consuming and costly. Consequently, there is a growing need to combine the
scalability of LLM-generated labels with the precision of human annotations,
enabling fine-tuned smaller models to achieve both higher speed and accuracy
comparable to larger models. In this paper, we introduce a simple yet effective
framework to address this challenge. Our approach is specifically designed for
per-utterance classification problems, which encompass tasks such as intent
detection, dialogue state tracking, and more. To mitigate the impact of
labeling errors from LLMs -- the primary source of inaccuracies in student
models -- we propose a noise-reduced preference learning loss. Experimental
results demonstrate that our method significantly improves accuracy across
utterance-level dialogue tasks, including sentiment detection (over \\(2%\\)),
dialogue act classification (over \\(1.5%\\)), etc.
