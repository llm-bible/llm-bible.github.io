---
layout: publication
title: 'Attentiondefense: Leveraging System Prompt Attention For Explainable Defense Against Novel Jailbreaks'
authors: Charlotte Siska, Anush Sankaran
conference: "Arxiv"
year: 2025
bibkey: siska2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12321"}
tags: ['Transformer', 'Agentic', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Security', 'Attention Mechanism', 'Prompting']
---
In the past few years, Language Models (LMs) have shown par-human
capabilities in several domains. Despite their practical applications and
exceeding user consumption, they are susceptible to jailbreaks when malicious
input exploits the LM's weaknesses, causing it to deviate from its intended
behavior. Current defensive strategies either classify the input prompt as
adversarial or prevent LMs from generating harmful outputs. However, it is
challenging to explain the reason behind the malicious nature of the jailbreak,
which results in a wide variety of closed-box approaches. In this research, we
propose and demonstrate that system-prompt attention from Small Language Models
(SLMs) can be used to characterize adversarial prompts, providing a novel,
explainable, and cheaper defense approach called AttentionDefense. Our research
suggests that the attention mechanism is an integral component in understanding
and explaining how LMs respond to malicious input that is not captured in the
semantic meaning of text embeddings. The proposed AttentionDefense is evaluated
against existing jailbreak benchmark datasets. Ablation studies show that
SLM-based AttentionDefense has equivalent or better jailbreak detection
performance compared to text embedding-based classifiers and GPT-4 zero-shot
detectors.To further validate the efficacy of the proposed approach, we
generate a dataset of novel jailbreak variants of the existing benchmark
dataset using a closed-loop LLM-based multi-agent system. We demonstrate that
the proposed AttentionDefense approach performs robustly on this novel
jailbreak dataset while existing approaches suffer in performance.
Additionally, for practical purposes AttentionDefense is an ideal solution as
it has the computation requirements of a small LM but the performance of a LLM
detector.
