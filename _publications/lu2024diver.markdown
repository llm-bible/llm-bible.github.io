---
layout: publication
title: Diver Large Language Model Decoding with Span-Level Mutual Information Verification
authors: Lu Jinliang, Wang Chen, Zhang Jiajun
conference: "Arxiv"
year: 2024
bibkey: lu2024diver
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02120"}
tags: ['Pretraining Methods']
---
Large language models (LLMs) have shown impressive capabilities in adapting to various tasks when provided with task-specific instructions. However LLMs using standard decoding strategies often struggle with deviations from the inputs. Intuitively compliant LLM outputs should reflect the information present in the input which can be measured by point-wise mutual information (PMI) scores. Therefore we propose Diver a novel approach that enhances LLM Decoding through span-level PMI verification. During inference Diver first identifies divergence steps that may lead to multiple candidate spans. Subsequently it calculates the PMI scores by assessing the log-likelihood gains of the input if the candidate spans are generated. Finally the optimal span is selected based on the PMI re-ranked output distributions. We evaluate our method across various downstream tasks and empirical results demonstrate that Diver significantly outperforms existing decoding methods in both performance and versatility.
