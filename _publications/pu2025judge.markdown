---
layout: publication
title: 'Judge Anything: MLLM As A Judge Across Any Modality'
authors: Shu Pu, Yaochen Wang, Dongping Chen, Yuhang Chen, Guohao Wang, Qi Qin, Zhongyi Zhang, Zhiyuan Zhang, Zetong Zhou, Shuang Gong, Yi Gui, Yao Wan, Philip S. Yu
conference: "Arxiv"
year: 2025
bibkey: pu2025judge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17489"}
  - {name: "Code", url: "https://urrealhero.github.io/judgeanythingweb/"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Ethics and Bias', 'Has Code']
---
Evaluating generative foundation models on open-ended multimodal
understanding (MMU) and generation (MMG) tasks across diverse modalities (e.g.,
images, audio, video) poses significant challenges due to the complexity of
cross-modal interactions. To this end, the idea of utilizing Multimodal LLMs
(MLLMs) as automated judges has emerged, with encouraging results in assessing
vision-language understanding tasks. Moving further, this paper extends
MLLM-as-a-Judge across modalities to a unified manner by introducing two
benchmarks, TaskAnything and JudgeAnything, to respectively evaluate the
overall performance and judging capabilities of MLLMs across any-to-any
modality tasks. Specifically, TaskAnything evaluates the MMU and MMG
capabilities across 15 any-to-any modality categories, employing 1,500 queries
curated from well-established benchmarks. Furthermore, JudgeAnything evaluates
the judging capabilities of 5 advanced (e.g., GPT-4o and Gemini-2.0-Flash) from
the perspectives of Pair Comparison and Score Evaluation, providing a
standardized testbed that incorporates human judgments and detailed rubrics.
Our extensive experiments reveal that while these MLLMs show promise in
assessing MMU (i.e., achieving an average of 66.55% in Pair Comparison setting
and 42.79% in Score Evaluation setting), they encounter significant challenges
with MMG tasks (i.e., averaging only 53.37% in Pair Comparison setting and
30.05% in Score Evaluation setting), exposing cross-modality biases and
hallucination issues. To address this, we present OmniArena, an automated
platform for evaluating omni-models and multimodal reward models. Our work
highlights the need for fairer evaluation protocols and stronger alignment with
human preferences. The source code and dataset are publicly available at:
https://urrealhero.github.io/judgeanythingweb/.
