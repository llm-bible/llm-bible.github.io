---
layout: publication
title: 'Wanda++: Pruning Large Language Models Via Regional Gradients'
authors: Yifan Yang, Kai Zhen, Bhavana Ganesh, Aram Galstyan, Goeric Huybrechts, Markus Müller, Jonas M. Kübler, Rupak Vignesh Swaminathan, Athanasios Mouchtaris, Sravan Babu Bodapati, Nathan Susanj, Zheng Zhang, Jack Fitzgerald, Abhishek Kumar
conference: "Arxiv"
year: 2025
bibkey: yang2025pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04992"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Language Modeling', 'Pruning', 'Pretraining Methods', 'Fine-Tuning']
---
Large Language Models (LLMs) pruning seeks to remove unimportant weights for inference speedup with minimal accuracy impact. However, existing methods often suffer from accuracy degradation without full-model sparsity-aware fine-tuning. This paper presents Wanda++, a novel pruning framework that outperforms the state-of-the-art methods by utilizing decoder-block-level \textbf\{regional\} gradients. Specifically, Wanda++ improves the pruning score with regional gradients for the first time and proposes an efficient regional optimization method to minimize pruning-induced output discrepancies between the dense and sparse decoder output. Notably, Wanda++ improves perplexity by up to 32% over Wanda in the language modeling task and generalizes effectively to downstream tasks. Moreover, despite updating weights with regional optimization, Wanda++ remains orthogonal to sparsity-aware fine-tuning, further reducing perplexity with LoRA in great extend. Our approach is lightweight, pruning a 7B LLaMA model in under 10 minutes on a single H100 GPU.
