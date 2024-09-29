---
layout: publication
title: "Detecting Edit Failures In Large Language Models: An Improved Specificity Benchmark"
authors: Hoelscher-obermaier Jason, Persson Julia, Kran Esben, Konstas Ioannis, Barez Fazl
conference: "Arxiv"
year: 2023
bibkey: hoelscherobermaier2023detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17553"}
tags: ['Ethics And Bias', 'Training Techniques']
---
Recent model editing techniques promise to mitigate the problem of memorizing false or outdated associations during LLM training. However we show that these techniques can introduce large unwanted side effects which are not detected by existing specificity benchmarks. We extend the existing CounterFact benchmark to include a dynamic component and dub our benchmark CounterFact+. Additionally we extend the metrics used for measuring specificity by a principled KL divergence-based metric. We use this improved benchmark to evaluate recent model editing techniques and find that they suffer from low specificity. Our findings highlight the need for improved specificity benchmarks that identify and prevent unwanted side effects.
