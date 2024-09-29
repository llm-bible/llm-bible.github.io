---
layout: publication
title: 'Exploring The Relationship Between In-context Learning And Instruction Tuning'
authors: Duan Hanyu, Tang Yixuan, Yang Yi, Abbasi Ahmed, Tam Kar Yan
conference: "Arxiv"
year: 2023
bibkey: duan2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10367"}
tags: ['Applications', 'In Context Learning', 'Prompting', 'Training Techniques']
---
In-Context Learning (ICL) and Instruction Tuning (IT) are two primary paradigms of adopting Large Language Models (LLMs) to downstream applications. However they are significantly different. In ICL a set of demonstrations are provided at inference time but the LLMs parameters are not updated. In IT a set of demonstrations are used to tune LLMs parameters in training time but no demonstrations are used at inference time. Although a growing body of literature has explored ICL and IT studies on these topics have largely been conducted in isolation leading to a disconnect between these two paradigms. In this work we explore the relationship between ICL and IT by examining how the hidden states of LLMs change in these two paradigms. Through carefully designed experiments conducted with LLaMA-2 (7B and 13B) we find that ICL is implicit IT. In other words ICL changes an LLMs hidden states as if the demonstrations were used to instructionally tune the model. Furthermore the convergence between ICL and IT is largely contingent upon several factors related to the provided demonstrations. Overall this work offers a unique perspective to explore the connection between ICL and IT and sheds light on understanding the behaviors of LLM.
