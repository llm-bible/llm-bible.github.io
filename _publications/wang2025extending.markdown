---
layout: publication
title: 'Logitlens4llms: Extending Logit Lens Analysis To Modern Large Language Models'
authors: Zhenyu Wang
conference: "Arxiv"
year: 2025
bibkey: wang2025extending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11667"}
  - {name: "Code", url: "https://github.com/zhenyu-02/LogitLens4LLMs"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
This paper introduces LogitLens4LLMs, a toolkit that extends the Logit Lens
technique to modern large language models. While Logit Lens has been a crucial
method for understanding internal representations of language models, it was
previously limited to earlier model architectures. Our work overcomes the
limitations of existing implementations, enabling the technique to be applied
to state-of-the-art architectures (such as Qwen-2.5 and Llama-3.1) while
automating key analytical workflows. By developing component-specific hooks to
capture both attention mechanisms and MLP outputs, our implementation achieves
full compatibility with the HuggingFace transformer library while maintaining
low inference overhead. The toolkit provides both interactive exploration and
batch processing capabilities, supporting large-scale layer-wise analyses.
Through open-sourcing our implementation, we aim to facilitate deeper
investigations into the internal mechanisms of large-scale language models. The
toolkit is openly available at https://github.com/zhenyu-02/LogitLens4LLMs.
