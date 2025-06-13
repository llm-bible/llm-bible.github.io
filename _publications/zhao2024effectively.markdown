---
layout: publication
title: 'Effectively Enhancing Vision Language Large Models By Prompt Augmentation And Caption Utilization'
authors: Minyi Zhao, Jie Wang, Zhaoyang Li, Jiyuan Zhang, Zhenbang Sun, Shuigeng Zhou
conference: "Arxiv"
year: 2024
bibkey: zhao2024effectively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14484"}
  - {name: "Code", url: "https://github.com/zhaominyiz/PACU"}
tags: ['Tools', 'Has Code', 'Prompting']
---
Recent studies have shown that Vision Language Large Models (VLLMs) may
output content not relevant to the input images. This problem, called the
hallucination phenomenon, undoubtedly degrades VLLM performance. Therefore,
various anti-hallucination techniques have been proposed to make model output
more reasonable and accurate. Despite their successes, from extensive tests we
found that augmenting the prompt (e.g. word appending, rewriting, and spell
error etc.) may change model output and make the output hallucinate again. To
cure this drawback, we propose a new instruct-tuning framework called Prompt
Augmentation and Caption Utilization (PACU) to boost VLLM's generation ability
under the augmented prompt scenario. Concretely, on the one hand, PACU exploits
existing LLMs to augment and evaluate diverse prompts automatically. The
resulting high-quality prompts are utilized to enhance VLLM's ability to
process different prompts. On the other hand, PACU exploits image captions to
jointly work with image features as well as the prompts for response
generation. When the visual feature is inaccurate, LLM can capture useful
information from the image captions for response generation. Extensive
experiments on hallucination evaluation and prompt-augmented datasets
demonstrate that our PACU method can work well with existing schemes to
effectively boost VLLM model performance. Code is available in
https://github.com/zhaominyiz/PACU.
