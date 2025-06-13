---
layout: publication
title: 'Improv: Inpainting-based Multimodal Prompting For Computer Vision Tasks'
authors: Jiarui Xu, Yossi Gandelsman, Amir Bar, Jianwei Yang, Jianfeng Gao, Trevor Darrell, Xiaolong Wang
conference: "Arxiv"
year: 2023
bibkey: xu2023inpainting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01771"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Prompting', 'In-Context Learning']
---
In-context learning allows adapting a model to new tasks given a task
description at test time. In this paper, we present IMProv - a generative model
that is able to in-context learn visual tasks from multimodal prompts. Given a
textual description of a visual task (e.g. "Left: input image, Right:
foreground segmentation"), a few input-output visual examples, or both, the
model in-context learns to solve it for a new test input. We train a masked
generative transformer on a new dataset of figures from computer vision papers
and their associated captions, together with a captioned large-scale image-text
dataset. During inference time, we prompt the model with text and/or image task
example(s) and have the model inpaint the corresponding output. We show that
training our model with text conditioning and scaling the dataset size improves
in-context learning for computer vision tasks by over +10% AP for Foreground
Segmentation, over +5% gains in AP for Single Object Detection, and almost
20% lower LPIPS in Colorization. Our empirical results suggest that vision and
language prompts are complementary and it is advantageous to use both to
achieve better in-context learning performance. Project page is available at
https://jerryxu.net/IMProv .
