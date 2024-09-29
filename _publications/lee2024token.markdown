---
layout: publication
title: Token45;supervised Value Models For Enhancing Mathematical Reasoning Capabilities Of Large Language Models
authors: Lee Jung Hyun, Yang June Yong, Heo Byeongho, Han Dongyoon, Yoo Kang Min
conference: "Arxiv"
year: 2024
bibkey: lee2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12863"}
tags: ['GPT', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated impressive problem45;solving capabilities in mathematics through step45;by45;step reasoning chains. However they are susceptible to reasoning errors that impact the quality of subsequent reasoning chains and the final answer due to language models autoregressive token45;by45;token generating nature. Recent works have proposed adopting external verifiers to guide the generation of reasoning paths but existing works utilize models that have been trained with step45;by45;step labels to assess the correctness of token45;by45;token reasoning chains. Consequently they struggle to recognize discriminative details of tokens within a reasoning path and lack the ability to evaluate whether an intermediate reasoning path is on a promising track toward the correct final answer. To amend the lack of sound and token45;grained math45;verification signals we devise a novel training scheme for verifiers that apply token45;level supervision with the expected cumulative reward (i.e. value). Furthermore we propose a practical formulation of the cumulative reward by reducing it to finding the probability of future correctness of the final answer and thereby enabling the empirical estimation of the value. Experimental results on mathematical reasoning benchmarks show that Token45;Supervised Value Model (TVM) can outperform step45;by45;step verifiers on GSM8K and MATH with Mistral and Llama.
