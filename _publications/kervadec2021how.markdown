---
layout: publication
title: How Transferable Are Reasoning Patterns In VQA?
authors: Kervadec Corentin, Jaunet Theo, Antipov Grigory, Baccouche Moez, Vuillemot Romain, Wolf Christian
conference: "Arxiv"
year: 2021
bibkey: kervadec2021how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.03656"}
  - {name: "Code", url: "https://reasoningpatterns.github.io)"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Since its inception Visual Question Answering (VQA) is notoriously known as a task where models are prone to exploit biases in datasets to find shortcuts instead of performing high-level reasoning. Classical methods address this by removing biases from training data or adding branches to models to detect and remove biases. In this paper we argue that uncertainty in vision is a dominating factor preventing the successful learning of reasoning in vision and language problems. We train a visual oracle and in a large scale study provide experimental evidence that it is much less prone to exploiting spurious dataset biases compared to standard models. We propose to study the attention mechanisms at work in the visual oracle and compare them with a SOTA Transformer-based model. We provide an in-depth analysis and visualizations of reasoning patterns obtained with an online visualization tool which we make publicly available (https://reasoningpatterns.github.io). We exploit these insights by transferring reasoning patterns from the oracle to a SOTA Transformer-based VQA model taking standard noisy visual inputs via fine-tuning. In experiments we report higher overall accuracy as well as accuracy on infrequent answers for each question type which provides evidence for improved generalization and a decrease of the dependency on dataset biases.
