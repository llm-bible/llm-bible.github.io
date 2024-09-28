---
layout: publication
title: Enhancing Healthcare LLM Trust with Atypical Presentations Recalibration
authors: Qin Jeremy, Liu Bang, Nguyen Quoc Dinh
conference: "Arxiv"
year: 2024
bibkey: qin2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03225"}
tags: ['ARXIV', 'Applications', 'LLM']
---
Black-box large language models (LLMs) are increasingly deployed in various environments making it essential for these models to effectively convey their confidence and uncertainty especially in high-stakes settings. However these models often exhibit overconfidence leading to potential risks and misjudgments. Existing techniques for eliciting and calibrating LLM confidence have primarily focused on general reasoning datasets yielding only modest improvements. Accurate calibration is crucial for informed decision-making and preventing adverse outcomes but remains challenging due to the complexity and variability of tasks these models perform. In this work we investigate the miscalibration behavior of black-box LLMs within the healthcare setting. We propose a novel method which leverages atypical presentations to adjust the models confidence estimates. Our approach significantly improves calibration reducing calibration errors by approximately 60 on three medical question answering datasets and outperforming existing methods such as vanilla verbalized confidence CoT verbalized confidence and others. Additionally we provide an in-depth analysis of the role of atypicality within the recalibration framework.
