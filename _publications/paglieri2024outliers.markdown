---
layout: publication
title: 'Outliers And Calibration Sets Have Diminishing Effect On Quantization Of Modern Llms'
authors: Paglieri Davide, Dash Saurabh, Rocktäschel Tim, Parker-holder Jack
conference: "Arxiv"
year: 2024
bibkey: paglieri2024outliers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20835"}
tags: ['Efficiency And Optimization', 'Merging', 'Quantization', 'Security', 'Training Techniques']
---
Post-Training Quantization (PTQ) enhances the efficiency of Large Language Models (LLMs) by enabling faster operation and compatibility with more accessible hardware through reduced memory usage at the cost of small performance drops. We explore the role of calibration sets in PTQ specifically their effect on hidden activations in various notable open-source LLMs. Calibration sets are crucial for evaluating activation magnitudes and identifying outliers which can distort the quantization range and negatively impact performance. Our analysis reveals a marked contrast in quantization effectiveness across models. The older OPT model upon which much of the quantization literature is based shows significant performance deterioration and high susceptibility to outliers with varying calibration sets. In contrast newer models like Llama-2 7B Llama-3 8B Command-R 35B and Mistral 7B demonstrate strong robustness with Mistral 7B showing near-immunity to outliers and stable activations. These findings suggest a shift in PTQ strategies might be needed. As advancements in pre-training methods reduce the relevance of outliers there is an emerging need to reassess the fundamentals of current quantization literature. The emphasis should pivot towards optimizing inference speed rather than primarily focusing on outlier preservation to align with the evolving characteristics of state-of-the-art LLMs.
