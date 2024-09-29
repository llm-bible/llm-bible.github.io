---
layout: publication
title: 'Can Mllms Perform Text-to-image In-context Learning?'
authors: Zeng Yuchen, Kang Wonjun, Chen Yicong, Koo Hyung Il, Lee Kangwook
conference: "Arxiv"
year: 2024
bibkey: zeng2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01293"}
  - {name: "Code", url: "https://github.com/UW-Madison-Lee-Lab/CoBSAT"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'In Context Learning', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
The evolution from Large Language Models (LLMs) to Multimodal Large Language Models (MLLMs) has spurred research into extending In-Context Learning (ICL) to its multimodal counterpart. Existing such studies have primarily concentrated on image-to-text ICL. However the Text-to-Image ICL (T2I-ICL) with its unique characteristics and potential applications remains underexplored. To address this gap we formally define the task of T2I-ICL and present CoBSAT the first T2I-ICL benchmark dataset encompassing ten tasks. Utilizing our dataset to benchmark six state-of-the-art MLLMs we uncover considerable difficulties MLLMs encounter in solving T2I-ICL. We identify the primary challenges as the inherent complexity of multimodality and image generation and show that strategies such as fine-tuning and Chain-of-Thought prompting help to mitigate these difficulties leading to notable improvements in performance. Our code and dataset are available at https://github.com/UW-Madison-Lee-Lab/CoBSAT."
