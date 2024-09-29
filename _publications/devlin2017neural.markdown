---
layout: publication
title: Robustfill&#58; Neural Program Learning Under Noisy I/O
authors: Devlin Jacob, Uesato Jonathan, Bhupatiraju Surya, Singh Rishabh, Mohamed Abdel-rahman, Kohli Pushmeet
conference: "Arxiv"
year: 2017
bibkey: devlin2017neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1703.07469"}
tags: ['Attention Mechanism', 'Model Architecture', 'Reinforcement Learning']
---
The problem of automatically generating a computer program from some specification has been studied since the early days of AI. Recently two competing approaches for automatic program learning have received significant attention (1) neural program synthesis where a neural network is conditioned on input/output (I/O) examples and learns to generate a program and (2) neural program induction where a neural network generates new outputs directly using a latent program representation. Here for the first time we directly compare both approaches on a large-scale real-world learning task. We additionally contrast to rule-based program synthesis which uses hand-crafted semantics to guide the program generation. Our neural models use a modified attention RNN to allow encoding of variable-sized sets of I/O pairs. Our best synthesis model achieves 9237; accuracy on a real-world test set compared to the 3437; accuracy of the previous best neural synthesis approach. The synthesis model also outperforms a comparable induction model on this task but we more importantly demonstrate that the strength of each approach is highly dependent on the evaluation metric and end-user application. Finally we show that we can train our neural models to remain very robust to the type of noise expected in real-world data (e.g. typos) while a highly-engineered rule-based system fails entirely.
