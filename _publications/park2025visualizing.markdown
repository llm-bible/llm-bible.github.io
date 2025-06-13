---
layout: publication
title: 'Visualizing Uncertainty In Translation Tasks: An Evaluation Of LLM Performance And Confidence Metrics'
authors: Jin Hyun Park, Utsawb Laminchhane, Umer Farooq, Uma Sivakumar, Arpan Kumar
conference: "Arxiv"
year: 2025
bibkey: park2025visualizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17187"}
tags: ['Tools', 'Applications', 'Interpretability and Explainability', 'WMT', 'Reinforcement Learning']
---
Large language models (LLMs) are increasingly utilized for machine
translation, yet their predictions often exhibit uncertainties that hinder
interpretability and user trust. Effectively visualizing these uncertainties
can enhance the usability of LLM outputs, particularly in contexts where
translation accuracy is critical. This paper addresses two primary objectives:
(1) providing users with token-level insights into model confidence and (2)
developing a web-based visualization tool to quantify and represent translation
uncertainties. To achieve these goals, we utilized the T5 model with the WMT19
dataset for translation tasks and evaluated translation quality using
established metrics such as BLEU, METEOR, and ROUGE. We introduced three novel
uncertainty quantification (UQ) metrics: (1) the geometric mean of token
probabilities, (2) the arithmetic mean of token probabilities, and (3) the
arithmetic mean of the kurtosis of token distributions. These metrics provide a
simple yet effective framework for evaluating translation performance. Our
analysis revealed a linear relationship between the traditional evaluation
metrics and our UQ metrics, demonstrating the validity of our approach.
Additionally, we developed an interactive web-based visualization that uses a
color gradient to represent token confidence. This tool offers users a clear
and intuitive understanding of translation quality while providing valuable
insights into model performance. Overall, we show that our UQ metrics and
visualization are both robust and interpretable, offering practical tools for
evaluating and accessing machine translation systems.
