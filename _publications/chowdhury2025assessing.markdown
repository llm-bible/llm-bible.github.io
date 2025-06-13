---
layout: publication
title: 'Avtrustbench: Assessing And Enhancing Reliability And Robustness In Audio-visual Llms'
authors: Sanjoy Chowdhury, Sayan Nag, Subhrajyoti Dasgupta, Yaoting Wang, Mohamed Elhoseiny, Ruohan Gao, Dinesh Manocha
conference: "Arxiv"
year: 2025
bibkey: chowdhury2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02135"}
tags: ['Security', 'Training Techniques', 'Tools', 'Efficiency and Optimization']
---
With the rapid advancement of Multi-modal Large Language Models (MLLMs),
several diagnostic benchmarks have recently been developed to assess these
models' multi-modal reasoning proficiency. However, these benchmarks are
restricted to assessing primarily the visual aspect and do not examine the
holistic audio-visual (AV) understanding. Moreover, currently, there are no
benchmarks that investigate the capabilities of AVLLMs to calibrate their
responses when presented with perturbed inputs. To this end, we introduce
Audio-Visual Trustworthiness assessment Benchmark (AVTrustBench), comprising
600K samples spanning over 9 meticulously crafted tasks, evaluating the
capabilities of AVLLMs across three distinct dimensions: Adversarial attack,
Compositional reasoning, and Modality-specific dependency. Using our benchmark
we extensively evaluate 13 state-of-the-art AVLLMs. The findings reveal that
the majority of existing models fall significantly short of achieving
human-like comprehension, offering valuable insights for future research
directions. To alleviate the limitations in the existing approaches, we further
propose a robust, model-agnostic calibrated audio-visual preference
optimization based training strategy CAVPref, obtaining a gain up to 30.19%
across all 9 tasks. We will publicly release our code and benchmark to
facilitate future research in this direction.
