---
layout: publication
title: 'Breaking The Language Barrier: Improving Cross-lingual Reasoning With Structured Self-attention'
authors: Foroutan Negar, Banaei Mohammadreza, Aberer Karl, Bosselut Antoine
conference: "Arxiv"
year: 2023
bibkey: foroutan2023breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15258"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Transformer']
---
"In this work, we study whether multilingual language models (MultiLMs) can transfer logical reasoning abilities to other languages when they are fine-tuned for reasoning in a different language. We evaluate the cross-lingual reasoning abilities of MultiLMs in two schemes: (1) where the language of the context and the question remain the same in the new languages that are tested (i.e., the reasoning is still monolingual, but the model must transfer the learned reasoning ability across languages), and (2) where the language of the context and the question is different (which we term code-switched reasoning). On two logical reasoning datasets, RuleTaker and LeapOfThought, we demonstrate that although MultiLMs can transfer reasoning ability across languages in a monolingual setting, they struggle to transfer reasoning abilities in a code-switched setting. Following this observation, we propose a novel attention mechanism that uses a dedicated set of parameters to encourage cross-lingual attention in code-switched sequences, which improves the reasoning performance by up to 14&#37; and 4&#37; on the RuleTaker and LeapOfThought datasets, respectively."
