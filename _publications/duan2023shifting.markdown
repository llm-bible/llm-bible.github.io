---
layout: publication
title: Shifting Attention To Relevance\: Towards The Predictive Uncertainty Quantification Of Free-form Large Language Models
authors: Duan Jinhao, Cheng Hao, Wang Shiqi, Zavalny Alex, Wang Chenan, Xu Renjing, Kailkhura Bhavya, Xu Kaidi
conference: "Arxiv"
year: 2023
bibkey: duan2023shifting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.01379"}
  - {name: "Code", url: "https://github.com/jinhaoduan/SAR"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) show promising results in language generation and instruction following but frequently hallucinate making their outputs less reliable. Despite Uncertainty Quantifications (UQ) potential solutions implementing it accurately within LLMs is challenging. Our research introduces a simple heuristic not all tokens in auto-regressive LLM text equally represent the underlying meaning as linguistic redundancy often allows a few keywords to convey the essence of long sentences. However current methods underestimate this inequality when assessing uncertainty causing tokens with limited semantics to be equally or excessively weighted in UQ. To correct this we propose Shifting Attention to more Relevant (SAR) components at both token- and sentence-levels for better UQ. We conduct extensive experiments involving a range of popular off-the-shelf LLMs such as Vicuna WizardLM and LLaMA-2-chat with model sizes extending up to 33B parameters. We evaluate various free-form question-answering tasks encompassing domains such as reading comprehension science Qamp;A and medical Qamp;A. Our experimental results coupled with a comprehensive demographic analysis demonstrate the superior performance of SAR. The code is available at https://github.com/jinhaoduan/SAR."
