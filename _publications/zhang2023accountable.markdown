---
layout: publication
title: Accountable Textual45;visual Chat Learns To Reject Human Instructions In Image Re45;creation
authors: Zhang Zhiwei, Liu Yuliang
conference: "Arxiv"
year: 2023
bibkey: zhang2023accountable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.05983"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Responsible AI', 'Training Techniques', 'Transformer']
---
The recent success of ChatGPT and GPT45;4 has drawn widespread attention to multimodal dialogue systems. However there is a lack of datasets in the academic community that can effectively evaluate the multimodal generation capabilities of Visual Language Models (VLMs) in textual45;visual chat tasks. In this paper we address this gap by introducing two novel multimodal datasets the synthetic CLEVR45;ATVC dataset (620K) and the manually pictured Fruit45;ATVC dataset (50K). These datasets incorporate both visual and text45;based inputs and outputs. Furthermore to facilitate the accountability of multimodal systems in rejecting human requests similar to language45;based ChatGPT conversations we introduce specific rules as supervisory signals within the datasets. This allows the trained VLM to provide a yes or no answer after engaging in visual and textual reasoning accompanied by a language explanation to clarify the reasons behind the inability to execute the given human instruction. Our proposed method involves a two45;stage training procedure which includes training the image auto45;encoder and the auto45;regressive transformer from scratch. The first stage employs a discrete variational autoencoder (dVAE) to compress each image into concise tokens which are then combined with text tokens into a single data stream. This stream is subsequently fed into the decoder45;based transformer to generate visual re45;creations and textual feedback in the second stage. We conduct comprehensive analyses of experimental results focusing on re45;created image quality answer accuracy and the models behavior when faced with uncertainty and imperfect user queries. Through our explorations and findings we aim to contribute valuable insights into the accountability of textual45;visual generative models.
