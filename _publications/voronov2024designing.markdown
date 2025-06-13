---
layout: publication
title: 'Switti: Designing Scale-wise Transformers For Text-to-image Synthesis'
authors: Anton Voronov, Denis Kuznedelev, Mikhail Khoroshikh, Valentin Khrulkov, Dmitry Baranchuk
conference: "Arxiv"
year: 2024
bibkey: voronov2024designing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01819"}
tags: ['Training Techniques', 'Model Architecture', 'Merging', 'GPT', 'Pretraining Methods', 'Transformer']
---
This work presents Switti, a scale-wise transformer for text-to-image
generation. We start by adapting an existing next-scale prediction
autoregressive (AR) architecture to T2I generation, investigating and
mitigating training stability issues in the process. Next, we argue that
scale-wise transformers do not require causality and propose a non-causal
counterpart facilitating ~21% faster sampling and lower memory usage while also
achieving slightly better generation quality. Furthermore, we reveal that
classifier-free guidance at high-resolution scales is often unnecessary and can
even degrade performance. By disabling guidance at these scales, we achieve an
additional sampling acceleration of ~32% and improve the generation of
fine-grained details. Extensive human preference studies and automated
evaluations show that Switti outperforms existing T2I AR models and competes
with state-of-the-art T2I diffusion models while being up to 7x faster.
