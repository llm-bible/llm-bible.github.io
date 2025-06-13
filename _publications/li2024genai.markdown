---
layout: publication
title: 'Genai-bench: Evaluating And Improving Compositional Text-to-visual Generation'
authors: Baiqi Li, Zhiqiu Lin, Deepak Pathak, Jiayao Li, Yixin Fei, Kewen Wu, Tiffany Ling, Xide Xia, Pengchuan Zhang, Graham Neubig, Deva Ramanan
conference: "Arxiv"
year: 2024
bibkey: li2024genai
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13743'}
tags: ['Reinforcement Learning', 'Prompting', 'Merging']
---
While text-to-visual models now produce photo-realistic images and videos,
they struggle with compositional text prompts involving attributes,
relationships, and higher-order reasoning such as logic and comparison. In this
work, we conduct an extensive human study on GenAI-Bench to evaluate the
performance of leading image and video generation models in various aspects of
compositional text-to-visual generation. We also compare automated evaluation
metrics against our collected human ratings and find that VQAScore -- a metric
measuring the likelihood that a VQA model views an image as accurately
depicting the prompt -- significantly outperforms previous metrics such as
CLIPScore. In addition, VQAScore can improve generation in a black-box manner
(without finetuning) via simply ranking a few (3 to 9) candidate images.
Ranking by VQAScore is 2x to 3x more effective than other scoring methods like
PickScore, HPSv2, and ImageReward at improving human alignment ratings for
DALL-E 3 and Stable Diffusion, especially on compositional prompts that require
advanced visio-linguistic reasoning. We release a new GenAI-Rank benchmark with
over 40,000 human ratings to evaluate scoring metrics on ranking images
generated from the same prompt. Lastly, we discuss promising areas for
improvement in VQAScore, such as addressing fine-grained visual details. We
will release all human ratings (over 80,000) to facilitate scientific
benchmarking of both generative models and automated metrics.
