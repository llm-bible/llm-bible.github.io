---
layout: publication
title: 'EAZY: Eliminating Hallucinations In Lvlms By Zeroing Out Hallucinatory Image Tokens'
authors: Liwei Che, Tony Qingze Liu, Jing Jia, Weiyi Qin, Ruixiang Tang, Vladimir Pavlovic
conference: "Arxiv"
year: 2025
bibkey: che2025eliminating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07772"}
tags: ['Training Techniques', 'Multimodal Models', 'Attention Mechanism', 'Model Architecture']
---
Despite their remarkable potential, Large Vision-Language Models (LVLMs)
still face challenges with object hallucination, a problem where their
generated outputs mistakenly incorporate objects that do not actually exist.
Although most works focus on addressing this issue within the language-model
backbone, our work shifts the focus to the image input source, investigating
how specific image tokens contribute to hallucinations. Our analysis reveals a
striking finding: a small subset of image tokens with high attention scores are
the primary drivers of object hallucination. By removing these hallucinatory
image tokens (only 1.5% of all image tokens), the issue can be effectively
mitigated. This finding holds consistently across different models and
datasets. Building on this insight, we introduce EAZY, a novel, training-free
method that automatically identifies and Eliminates hAllucinations by Zeroing
out hallucinatorY image tokens. We utilize EAZY for unsupervised object
hallucination detection, achieving 15% improvement compared to previous
methods. Additionally, EAZY demonstrates remarkable effectiveness in mitigating
hallucinations while preserving model utility and seamlessly adapting to
various LVLM architectures.
