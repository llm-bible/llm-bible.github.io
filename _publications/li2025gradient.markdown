---
layout: publication
title: 'Congrad:conflicting Gradient Filtering For Multilingual Preference Alignment'
authors: Jiangnan Li, Thuy-trang Vu, Christian Herold, Amirhossein Tebbifakhr, Shahram Khadivi, Gholamreza Haffari
conference: "Arxiv"
year: 2025
bibkey: li2025gradient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23777'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques', 'Tools']
---
Naive joint training of large language models (LLMs) for multilingual
preference alignment can suffer from negative interference. This is a known
issue in multilingual training, where conflicting objectives degrade overall
performance. However, the impact of this phenomenon in the context of
multilingual preference alignment remains largely underexplored. To address
this issue, we propose CONGRAD, a scalable and effective filtering method that
selects high-quality preference samples with minimal gradient conflicts across
languages. Our method leverages gradient surgery to retain samples aligned with
an aggregated multilingual update direction. Additionally, we incorporate a
sublinear gradient compression strategy that reduces memory overhead during
gradient accumulation. We integrate CONGRAD into self-rewarding framework and
evaluate on LLaMA3-8B and Gemma2-2B across 10 languages. Results show that
CONGRAD consistently outperforms strong baselines in both seen and unseen
languages, with minimal alignment tax.
