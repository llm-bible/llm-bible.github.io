---
layout: publication
title: 'LLMCL-GEC: Advancing Grammatical Error Correction With Llm-driven Curriculum Learning'
authors: Tao Fang, Derek F. Wong, Lusheng Zhang, Keyan Jin, Qiang Zhang, Tianjiao Li, Jinlong Hou, Lidia S. Chao
conference: "Arxiv"
year: 2024
bibkey: fang2024llmcl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12541"}
tags: ['RAG', 'Training Techniques', 'Tools']
---
While large-scale language models (LLMs) have demonstrated remarkable
capabilities in specific natural language processing (NLP) tasks, they may
still lack proficiency compared to specialized models in certain domains, such
as grammatical error correction (GEC). Drawing inspiration from the concept of
curriculum learning, we have delved into refining LLMs into proficient GEC
experts by devising effective curriculum learning (CL) strategies. In this
paper, we introduce a novel approach, termed LLM-based curriculum learning,
which capitalizes on the robust semantic comprehension and discriminative
prowess inherent in LLMs to gauge the complexity of GEC training data. Unlike
traditional curriculum learning techniques, our method closely mirrors human
expert-designed curriculums. Leveraging the proposed LLM-based CL method, we
sequentially select varying levels of curriculums ranging from easy to hard,
and iteratively train and refine using the pretrianed T5 and LLaMA series
models. Through rigorous testing and analysis across diverse benchmark
assessments in English GEC, including the CoNLL14 test, BEA19 test, and BEA19
development sets, our approach showcases a significant performance boost over
baseline models and conventional curriculum learning methodologies.
