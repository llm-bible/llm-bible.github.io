---
layout: publication
title: Genception Evaluate Multimodal Llms With Unlabeled Unimodal Data
authors: Cao Lele, Buchner Valentin, Senane Zineb, Yang Fangkai
conference: "Arxiv"
year: 2024
bibkey: cao2024evaluate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14973"}
tags: ['Merging', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Multimodal Large Language Models (MLLMs) are typically assessed using expensive annotated multimodal benchmarks which often lag behind the rapidly evolving demands of MLLM evaluation. This paper outlines and validates GenCeption a novel annotation45;free evaluation method that requires only unimodal data to measure inter45;modality semantic coherence and inversely assesses MLLMs tendency to hallucinate. This approach eliminates the need for costly data annotation minimizes the risk of training data contamination results in slower benchmark saturation and avoids the illusion of emerging abilities. Inspired by the DrawCeption game GenCeption begins with a non45;textual sample and proceeds through iterative description and generation steps. The semantic drift across iterations is quantified using the GC35;64;T metric. Based on the GenCeption method we establish the MMECeption benchmark for evaluating Vision LLMs (VLLMs) and compare performance of several popular VLLMs and human annotators. Our empirical results validate GenCeptions effectiveness demonstrating strong correlations with established VLLM benchmarks. VLLMs still significantly lack behind human performance and struggle especially with text45;intensive tasks.
