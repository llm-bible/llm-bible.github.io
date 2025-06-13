---
layout: publication
title: 'Temple:temporal Preference Learning Of Video Llms Via Difficulty Scheduling And Pre-sft Alignment'
authors: Shicheng Li, Lei Li, Kun Ouyang, Shuhuai Ren, Yuanxin Liu, Yuanxing Zhang, Fuzheng Zhang, Lingpeng Kong, Qi Liu, Xu Sun
conference: "Arxiv"
year: 2025
bibkey: li2025preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16929"}
  - {name: "Code", url: "https://github.com/lscpku/TEMPLE"}
tags: ['Security', 'Model Architecture', 'Efficiency and Optimization', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Video Large Language Models (Video LLMs) have achieved significant success by
leveraging a two-stage paradigm: pretraining on large-scale video-text data for
vision-language alignment, followed by supervised fine-tuning (SFT) for
task-specific capabilities. However, existing approaches struggle with temporal
reasoning due to weak temporal correspondence in the data and reliance on the
next-token prediction paradigm during training. To address these limitations,
we propose TEMPLE (TEMporal Preference Learning), a systematic framework that
enhances Video LLMs' temporal reasoning capabilities through Direct Preference
Optimization (DPO). To facilitate this, we introduce an automated preference
data generation pipeline that systematically constructs preference pairs by
selecting videos that are rich in temporal information, designing
video-specific perturbation strategies, and finally evaluating model responses
on clean and perturbed video inputs. Our temporal alignment features two key
innovations: curriculum learning which that progressively increases
perturbation difficulty to improve model robustness and adaptability; and
"Pre-SFT Alignment'', applying preference optimization before instruction
tuning to prioritize fine-grained temporal comprehension. Extensive experiments
demonstrate that our approach consistently improves Video LLM performance
across multiple benchmarks with a relatively small set of self-generated DPO
data. We further analyze the transferability of DPO data across architectures
and the role of difficulty scheduling in optimization. Our findings highlight
our TEMPLE as a scalable and efficient complement to SFT-based methods, paving
the way for developing reliable Video LLMs. Code is available at
https://github.com/lscpku/TEMPLE.
