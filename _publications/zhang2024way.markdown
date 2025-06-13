---
layout: publication
title: 'Way To Specialist: Closing Loop Between Specialized LLM And Evolving Domain Knowledge Graph'
authors: Yutong Zhang, Lixing Chen, Shenghong Li, Nan Cao, Yang Shi, Jiaxin Ding, Zhe Qu, Pan Zhou, Yang Bai
conference: "Arxiv"
year: 2024
bibkey: zhang2024way
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19064'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated exceptional performance across
a wide variety of domains. Nonetheless, generalist LLMs continue to fall short
in reasoning tasks necessitating specialized knowledge. Prior investigations
into specialized LLMs focused on domain-specific training, which entails
substantial efforts in domain data acquisition and model parameter fine-tuning.
To address these challenges, this paper proposes the Way-to-Specialist (WTS)
framework, which synergizes retrieval-augmented generation with knowledge
graphs (KGs) to enhance the specialized capability of LLMs in the absence of
specialized training. In distinction to existing paradigms that merely utilize
external knowledge from general KGs or static domain KGs to prompt LLM for
enhanced domain-specific reasoning, WTS proposes an innovative
"LLM\\(\circlearrowright\\)KG" paradigm, which achieves bidirectional enhancement
between specialized LLM and domain knowledge graph (DKG). The proposed paradigm
encompasses two closely coupled components: the DKG-Augmented LLM and the
LLM-Assisted DKG Evolution. The former retrieves question-relevant domain
knowledge from DKG and uses it to prompt LLM to enhance the reasoning
capability for domain-specific tasks; the latter leverages LLM to generate new
domain knowledge from processed tasks and use it to evolve DKG. WTS closes the
loop between DKG-Augmented LLM and LLM-Assisted DKG Evolution, enabling
continuous improvement in the domain specialization as it progressively answers
and learns from domain-specific questions. We validate the performance of WTS
on 6 datasets spanning 5 domains. The experimental results show that WTS
surpasses the previous SOTA in 4 specialized domains and achieves a maximum
performance improvement of 11.3%.
