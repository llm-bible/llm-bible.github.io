---
layout: publication
title: 'Accountable Textual-visual Chat Learns To Reject Human Instructions In Image Re-creation'
authors: Zhiwei Zhang, Yuliang Liu
conference: "Arxiv"
year: 2023
bibkey: zhang2023accountable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.05983"}
tags: ['Fine-Tuning', 'Responsible AI', 'Transformer', 'GPT', 'Applications', 'Interpretability and Explainability', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
The recent success of ChatGPT and GPT-4 has drawn widespread attention to
multimodal dialogue systems. However, there is a lack of datasets in the
academic community that can effectively evaluate the multimodal generation
capabilities of Visual Language Models (VLMs) in textual-visual chat tasks. In
this paper, we address this gap by introducing two novel multimodal datasets:
the synthetic CLEVR-ATVC dataset (620K) and the manually pictured Fruit-ATVC
dataset (50K). These datasets incorporate both visual and text-based inputs and
outputs. Furthermore, to facilitate the accountability of multimodal systems in
rejecting human requests, similar to language-based ChatGPT conversations, we
introduce specific rules as supervisory signals within the datasets. This
allows the trained VLM to provide a yes or no answer after engaging in visual
and textual reasoning, accompanied by a language explanation to clarify the
reasons behind the inability to execute the given human instruction. Our
proposed method involves a two-stage training procedure, which includes
training the image auto-encoder and the auto-regressive transformer from
scratch. The first stage employs a discrete variational autoencoder (dVAE) to
compress each image into concise tokens, which are then combined with text
tokens into a single data stream. This stream is subsequently fed into the
decoder-based transformer to generate visual re-creations and textual feedback
in the second stage. We conduct comprehensive analyses of experimental results,
focusing on re-created image quality, answer accuracy, and the model's behavior
when faced with uncertainty and imperfect user queries. Through our
explorations and findings, we aim to contribute valuable insights into the
accountability of textual-visual generative models.
