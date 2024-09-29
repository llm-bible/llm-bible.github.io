---
layout: publication
title: Non45;instructional Fine45;tuning Enabling Instruction45;following Capabilities In Pre45;trained Language Models Without Instruction45;following Data
authors: Xie Juncheng, Syu Shensian, Lee Hung-yi
conference: "Arxiv"
year: 2024
bibkey: xie2024non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00096"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools']
---
Instruction fine45;tuning is crucial for todays large language models (LLMs) to learn to follow instructions and align with human preferences. Conventionally supervised data including the instruction and the correct response is required for instruction fine45;tuning. To obtain such data some researchers prompted well45;trained models like GPT45;4 to generate instructions and correct responses. In this paper we propose a novel approach that uses the first half of a random text from OpenWebText as the instruction and GPT45;3.545;turbo or GPT45;445;turbo to complete the text as the response. Despite the data being non45;instructional we found that pre45;trained LLMs fine45;tuned on this data can gain instruction45;following capabilities. This observation is verified by fine45;tuning several well45;known pre45;trained LLMs (e.g. LLaMA45;245;7B LLaMA45;345;8B LLaMA45;345;70B Mistral45;7B45;v0.1). The non45;instructional data also improved some models that underwent supervised fine45;tuning and human preference alignment. Our LLaMA45;345;70B45;Instruct fine45;tuned through non45;instructional data is comparable with LLaMA45;3.145;70B45;Instruct on the Arena Hard leaderboard. We analyzed the non45;instructional data and ensured it is devoid of content related to instruction fine45;tuning. Our findings will inspire further investigation into how to develop instruction45;following capabilities without explicit instruction45;related data.
