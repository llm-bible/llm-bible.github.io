---
layout: publication
title: 'Ai4math: A Native Spanish Benchmark For University-level Mathematical Reasoning In Large Language Models'
authors: Miguel Angel Peñaloza 1 And 2 And 5 Perez, Bruno Lopez 1 And 2 And 3 Orozco, Jesus Tadeo Cruz 1 And 2 And 4 Soto, Michelle Bruno 1 And 2 Hernandez, Miguel Angel Alvarado 1 And 2 Gonzalez, Sandra 1 And 2 Malagon
conference: "Arxiv"
year: 2025
bibkey: perez2025native
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18978'}
tags: ['GPT', 'Model Architecture']
---
Existing mathematical reasoning benchmarks are predominantly English only or translation-based, which can introduce semantic drift and mask languagespecific reasoning errors. To address this, we present AI4Math, a benchmark of 105 original university level math problems natively authored in Spanish. The dataset spans seven advanced domains (Algebra, Calculus, Geometry, Probability, Number Theory, Combinatorics, and Logic), and each problem is accompanied by a step by step human solution. We evaluate six large language models GPT 4o, GPT 4o mini, o3 mini, LLaMA 3.3 70B, DeepSeek R1 685B, and DeepSeek V3 685B under four configurations: zero shot and chain of thought, each in Spanish and English. The top models (o3 mini, DeepSeek R1 685B, DeepSeek V3 685B) achieve over 70% accuracy, whereas LLaMA 3.3 70B and GPT-4o mini remain below 40%. Most models show no significant performance drop between languages, with GPT 4o even performing better on Spanish problems in the zero shot setting. Geometry, Combinatorics, and Probability questions remain persistently challenging for all models. These results highlight the need for native-language benchmarks and domain-specific evaluations to reveal reasoning failures not captured by standard metrics.
