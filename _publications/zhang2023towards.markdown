---
layout: publication
title: Towards Perceiving Small Visual Details In Zero45;shot Visual Question Answering With Multimodal Llms
authors: Zhang Jiarui, Khayatkhoei Mahyar, Chhikara Prateek, Ilievski Filip
conference: "Arxiv"
year: 2023
bibkey: zhang2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16033"}
tags: ['Applications', 'Multimodal Models', 'RAG']
---
Multimodal Large Language Models (MLLMs) have recently achieved promising zero45;shot accuracy on visual question answering (VQA) 45;45; a fundamental task affecting various downstream applications and domains. Given the great potential for the broad use of these models it is important to investigate their limitations in dealing with different image and question properties. In this work we investigate whether MLLMs can perceive small details as well as large details in images. In particular we show that their zero45;shot accuracy in answering visual questions is very sensitive to the size of the visual subject of the question declining up to 4637; with size. Furthermore we show that this effect is causal by observing that human visual cropping can significantly mitigate their sensitivity to size. Inspired by the usefulness of human cropping we then propose five automatic visual cropping methods 45;45; leveraging either external localization models or the decision process of the given MLLM itself 45;45; as inference time mechanisms to improve the zero45;shot performance of MLLMs. We study their effectiveness on four popular VQA datasets and a subset of the VQAv2 dataset tailored towards fine visual details. Our findings suggest that MLLMs should be used with caution in detail45;sensitive VQA applications and that visual cropping is a promising direction to improve their zero45;shot performance. To facilitate further investigation of MLLMs behaviors our code and data are publicly released.
