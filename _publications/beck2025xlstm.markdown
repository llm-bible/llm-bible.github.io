---
layout: publication
title: 'Xlstm 7B: A Recurrent LLM For Fast And Efficient Inference'
authors: Maximilian Beck, Korbinian Pöppel, Phillip Lippe, Richard Kurle, Patrick M. Blies, Günter Klambauer, Sebastian Böck, Sepp Hochreiter
conference: "Arxiv"
year: 2025
bibkey: beck2025xlstm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13427"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Recent breakthroughs in solving reasoning, math and coding problems with
Large Language Models (LLMs) have been enabled by investing substantial
computation budgets at inference time. Therefore, inference speed is one of the
most critical properties of LLM architectures, and there is a growing need for
LLMs that are efficient and fast at inference. Recently, LLMs built on the
xLSTM architecture have emerged as a powerful alternative to Transformers,
offering linear compute scaling with sequence length and constant memory usage,
both highly desirable properties for efficient inference. However, such
xLSTM-based LLMs have yet to be scaled to larger models and assessed and
compared with respect to inference speed and efficiency. In this work, we
introduce xLSTM 7B, a 7-billion-parameter LLM that combines xLSTM's
architectural benefits with targeted optimizations for fast and efficient
inference. Our experiments demonstrate that xLSTM 7B achieves performance on
downstream tasks comparable to other similar-sized LLMs, while providing
significantly faster inference speeds and greater efficiency compared to Llama-
and Mamba-based LLMs. These results establish xLSTM 7B as the fastest and most
efficient 7B LLM, offering a solution for tasks that require large amounts of
test-time computation. Our work highlights xLSTM's potential as a foundational
architecture for methods building on heavy use of LLM inference. Our model
weights, model code and training code are open-source.
