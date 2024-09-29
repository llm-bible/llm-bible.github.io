---
layout: publication
title: Contrastive Decoding Improves Reasoning In Large Language Models
authors: O'brien Sean, Lewis Mike
conference: "Arxiv"
year: 2023
bibkey: obrien2023contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.09117"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Training Techniques']
---
We demonstrate that Contrastive Decoding 45;45; a simple computationally light and training45;free text generation method proposed by Li et al 2022 45;45; achieves large out45;of45;the45;box improvements over greedy decoding on a variety of reasoning tasks. Originally shown to improve the perceived quality of long45;form text generation Contrastive Decoding searches for strings that maximize a weighted difference in likelihood between strong and weak models. We show that Contrastive Decoding leads LLaMA45;65B to outperform LLaMA 2 GPT45;3.5 and PaLM 245;L on the HellaSwag commonsense reasoning benchmark and to outperform LLaMA 2 GPT45;3.5 and PaLM45;540B on the GSM8K math word reasoning benchmark in addition to improvements on a collection of other tasks. Analysis suggests that Contrastive Decoding improves over existing methods by preventing some abstract reasoning errors as well as by avoiding simpler modes such as copying sections of the input during chain45;of45;thought. Overall Contrastive Decoding outperforms nucleus sampling for long45;form generation and greedy decoding for reasoning tasks making it a powerful general purpose method for generating text from language models.
