---
layout: publication
title: 'Fake News Detection After LLM Laundering: Measurement And Explanation'
authors: Rupak Kumar Das, Jonathan Dodge
conference: "Arxiv"
year: 2025
bibkey: das2025fake
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18649"}
tags: ['Model Architecture', 'BERT', 'Interpretability and Explainability']
---
With their advanced capabilities, Large Language Models (LLMs) can generate
highly convincing and contextually relevant fake news, which can contribute to
disseminating misinformation. Though there is much research on fake news
detection for human-written text, the field of detecting LLM-generated fake
news is still under-explored. This research measures the efficacy of detectors
in identifying LLM-paraphrased fake news, in particular, determining whether
adding a paraphrase step in the detection pipeline helps or impedes detection.
This study contributes: (1) Detectors struggle to detect LLM-paraphrased fake
news more than human-written text, (2) We find which models excel at which
tasks (evading detection, paraphrasing to evade detection, and paraphrasing for
semantic similarity). (3) Via LIME explanations, we discovered a possible
reason for detection failures: sentiment shift. (4) We discover a worrisome
trend for paraphrase quality measurement: samples that exhibit sentiment shift
despite a high BERTSCORE. (5) We provide a pair of datasets augmenting existing
datasets with paraphrase outputs and scores. The dataset is available on GitHub
