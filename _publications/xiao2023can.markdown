---
layout: publication
title: Can I Trust Your Answer Visually Grounded Video Question Answering
authors: Xiao Junbin, Yao Angela, Li Yicong, Chua Tat Seng
conference: "Arxiv"
year: 2023
bibkey: xiao2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.01327"}
  - {name: "Code", url: "https://github.com/doc&#45;doc/NExT&#45;GQA"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We study visually grounded VideoQA in response to the emerging trends of utilizing pretraining techniques for video45;language understanding. Specifically by forcing vision45;language models (VLMs) to answer questions and simultaneously provide visual evidence we seek to ascertain the extent to which the predictions of such techniques are genuinely anchored in relevant video content versus spurious correlations from language or irrelevant visual context. Towards this we construct NExT45;GQA 45;45; an extension of NExT45;QA with 10.5K temporal grounding (or location) labels tied to the original QA pairs. With NExT45;GQA we scrutinize a series of state45;of45;the45;art VLMs. Through post45;hoc attention analysis we find that these models are extremely weak in substantiating the answers despite their strong QA performance. This exposes the limitation of current VLMs in making reliable predictions. As a remedy we further explore and propose a grounded45;QA method via Gaussian mask optimization and cross45;modal learning. Experiments with different backbones demonstrate that this grounding mechanism improves both grounding and QA. With these efforts we aim to push towards trustworthy VLMs in VQA systems. Our dataset and code are available at https://github.com/doc&#45;doc/NExT&#45;GQA.
