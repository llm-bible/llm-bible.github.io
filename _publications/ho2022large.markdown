---
layout: publication
title: Large Language Models Are Reasoning Teachers
authors: Namgyu Ho, Laura Schmid, Se-young Yun
conference: "Arxiv"
year: 2022
bibkey: ho2022large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2212.10071v2"}
  - {name: "Code", url: "https://github.com/itsnamgyu/reasoning&#45;teacher"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
Recent works have shown that chain45;of45;thought (CoT) prompting can elicit language models to solve complex reasoning tasks step45;by45;step. However prompt45;based CoT methods are dependent on very large models such as GPT45;3 175B which are prohibitive to deploy at scale. In this paper we use these large models as reasoning teachers to enable complex reasoning in smaller models and reduce model size requirements by several orders of magnitude. We propose Fine45;tune45;CoT a method that generates reasoning samples from very large teacher models to fine45;tune smaller models. We evaluate our method on a wide range of public models and complex tasks. We find that Fine45;tune45;CoT enables substantial reasoning capability in small models far outperforming prompt45;based baselines and even the teacher model in many tasks. Additionally we extend our method by leveraging the teacher models ability to generate multiple distinct rationales for each original sample. Enriching the fine45;tuning data with such diverse reasoning results in a substantial performance boost across datasets even for very small models. We conduct ablations and sample studies to understand the emergence of reasoning capabilities of student models. Our code implementation and data are available at https://github.com/itsnamgyu/reasoning&#45;teacher.
