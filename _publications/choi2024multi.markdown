---
layout: publication
title: Multi45;granularity Guided Fusion45;in45;decoder
authors: Choi Eunseong, Lee Hyeri, Lee Jongwuk
conference: "Arxiv"
year: 2024
bibkey: choi2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02581"}
tags: ['Applications', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Pruning']
---
In Open45;domain Question Answering (ODQA) it is essential to discern relevant contexts as evidence and avoid spurious ones among retrieved results. The model architecture that uses concatenated multiple contexts in the decoding phase i.e. Fusion45;in45;Decoder demonstrates promising performance but generates incorrect outputs from seemingly plausible contexts. To address this problem we propose the Multi45;Granularity guided Fusion45;in45;Decoder (MGFiD) discerning evidence across multiple levels of granularity. Based on multi45;task learning MGFiD harmonizes passage re45;ranking with sentence classification. It aggregates evident sentences into an anchor vector that instructs the decoder. Additionally it improves decoding efficiency by reusing the results of passage re45;ranking for passage pruning. Through our experiments MGFiD outperforms existing models on the Natural Questions (NQ) and TriviaQA (TQA) datasets highlighting the benefits of its multi45;granularity solution.
