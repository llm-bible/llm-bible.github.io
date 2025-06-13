---
layout: publication
title: 'Understanding And Rectifying Safety Perception Distortion In Vlms'
authors: Xiaohan Zou, Jian Kang, George Kesidis, Lu Lin
conference: "Arxiv"
year: 2025
bibkey: zou2025understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13095"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Multimodal Models']
---
Recent studies reveal that vision-language models (VLMs) become more
susceptible to harmful requests and jailbreak attacks after integrating the
vision modality, exhibiting greater vulnerability than their text-only LLM
backbones. To uncover the root cause of this phenomenon, we conduct an in-depth
analysis and identify a key issue: multimodal inputs introduce an
modality-induced activation shift toward a "safer" direction compared to their
text-only counterparts, leading VLMs to systematically overestimate the safety
of harmful inputs. We refer to this issue as safety perception distortion. To
mitigate such distortion, we propose Activation Shift Disentanglement and
Calibration (ShiftDC), a training-free method that decomposes and calibrates
the modality-induced activation shift to reduce the impact of modality on
safety. By isolating and removing the safety-relevant component, ShiftDC
restores the inherent safety alignment of the LLM backbone while preserving the
vision-language capabilities of VLMs. Empirical results demonstrate that
ShiftDC significantly enhances alignment performance on safety benchmarks
without impairing model utility.
