---
layout: publication
title: 'Mm-phyqa: Multimodal Physics Question-answering With Multi-image Cot Prompting'
authors: Avinash Anand, Janak Kapuriya, Apoorv Singh, Jay Saraf, Naman Lal, Astha Verma, Rushali Gupta, Rajiv Shah
conference: "Arxiv"
year: 2024
bibkey: anand2024mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08704"}
tags: ['Prompting', 'Multimodal Models', 'Model Architecture', 'GPT']
---
While Large Language Models (LLMs) can achieve human-level performance in
various tasks, they continue to face challenges when it comes to effectively
tackling multi-step physics reasoning tasks. To identify the shortcomings of
existing models and facilitate further research in this area, we curated a
novel dataset, MM-PhyQA, which comprises well-constructed, high schoollevel
multimodal physics problems. By evaluating the performance of contemporary LLMs
that are publicly available, both with and without the incorporation of
multimodal elements in these problems, we aim to shed light on their
capabilities. For generating answers for questions consisting of multimodal
input (in this case, images and text) we employed Zero-shot prediction using
GPT-4 and utilized LLaVA (LLaVA and LLaVA-1.5), the latter of which were
fine-tuned on our dataset. For evaluating the performance of LLMs consisting
solely of textual input, we tested the performance of the base and fine-tuned
versions of the Mistral-7B and LLaMA2-7b models. We also showcased the
performance of the novel Multi-Image Chain-of-Thought (MI-CoT) Prompting
technique, which when used to train LLaVA-1.5 13b yielded the best results when
tested on our dataset, with superior scores in most metrics and the highest
accuracy of 71.65% on the test set.
