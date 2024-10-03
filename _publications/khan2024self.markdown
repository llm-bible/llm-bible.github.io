---
layout: publication
title: 'Self-training Large Language Models For Improved Visual Program Synthesis With Visual Reinforcement'
authors: Khan Zaid, Bg Vijay Kumar, Schulter Samuel, Fu Yun, Chandraker Manmohan
conference: "Arxiv"
year: 2024
bibkey: khan2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04627"}
tags: ['Applications', 'Few Shot', 'In Context Learning', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Visual program synthesis is a promising approach to exploit the reasoning abilities of large language models for compositional computer vision tasks. Previous work has used few-shot prompting with frozen LLMs to synthesize visual programs. Training an LLM to write better visual programs is an attractive prospect, but it is unclear how to accomplish this. No dataset of visual programs for training exists, and acquisition of a visual program dataset cannot be easily crowdsourced due to the need for expert annotators. To get around the lack of direct supervision, we explore improving the program synthesis abilities of an LLM using feedback from interactive experience. We propose a method where we exploit existing annotations for a vision-language task to improvise a coarse reward signal for that task, treat the LLM as a policy, and apply reinforced self-training to improve the visual program synthesis ability of the LLM for that task. We describe a series of experiments on object detection, compositional visual question answering, and image-text retrieval, and show that in each case, the self-trained LLM outperforms or performs on par with few-shot frozen LLMs that are an order of magnitude larger. Website: https://zaidkhan.me/ViReP
