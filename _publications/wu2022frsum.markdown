---
layout: publication
title: FRSUM Towards Faithful Abstractive Summarization via Enhancing Factual Robustness
authors: Wu Wenhao, Li Wei, Liu Jiachen, Xiao Xinyan, Cao Ziqiang, Li Sujian, Wu Hua
conference: "Arxiv"
year: 2022
bibkey: wu2022frsum
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.00294"}
tags: ['Applications', 'Security', 'Training Techniques']
---
Despite being able to generate fluent and grammatical text current Seq2Seq summarization models still suffering from the unfaithful generation problem. In this paper we study the faithfulness of existing systems from a new perspective of factual robustness which is the ability to correctly generate factual information over adversarial unfaithful information. We first measure a models factual robustness by its success rate to defend against adversarial attacks when generating factual information. The factual robustness analysis on a wide range of current systems shows its good consistency with human judgments on faithfulness. Inspired by these findings we propose to improve the faithfulness of a model by enhancing its factual robustness. Specifically we propose a novel training strategy namely FRSUM which teaches the model to defend against both explicit adversarial samples and implicit factual adversarial perturbations. Extensive automatic and human evaluation results show that FRSUM consistently improves the faithfulness of various Seq2Seq models such as T5 BART.
