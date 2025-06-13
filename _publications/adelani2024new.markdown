---
layout: publication
title: 'Irokobench: A New Benchmark For African Languages In The Age Of Large Language Models'
authors: David Ifeoluwa Adelani, Jessica Ojo, Israel Abebe Azime, Jian Yun Zhuang, Jesujoba O. Alabi, Xuanli He, Millicent Ochieng, Sara Hooker, Andiswa Bukula, En-shiun Annie Lee, Chiamaka Chukwuneke, Happy Buzaaba, Blessing Sibanda, Godson Kalipe, Jonathan Mukiibi, Salomon Kabongo, Foutse Yuehgoh, Mmasibidi Setaka, Lolwethu Ndolela, Nkiruka Odu, Rooweither Mabuya, Shamsuddeen Hassan Muhammad, Salomey Osei, Sokhar Samb, Tadesse Kebede Guge, Tombekai Vangoni Sherman, Pontus Stenetorp
conference: "Arxiv"
year: 2024
bibkey: adelani2024new
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.03368'}
tags: ['Few-Shot', 'GPT', 'Applications', 'Model Architecture']
---
Despite the widespread adoption of Large language models (LLMs), their
remarkable capabilities remain limited to a few high-resource languages.
Additionally, many low-resource languages (\eg African languages) are often
evaluated only on basic text classification tasks due to the lack of
appropriate or comprehensive benchmarks outside of high-resource languages. In
this paper, we introduce IrokoBench -- a human-translated benchmark dataset for
17 typologically-diverse low-resource African languages covering three tasks:
natural language inference~(AfriXNLI), mathematical reasoning~(AfriMGSM), and
multi-choice knowledge-based question answering~(AfriMMLU). We use IrokoBench
to evaluate zero-shot, few-shot, and translate-test settings~(where test sets
are translated into English) across 10 open and six proprietary LLMs. Our
evaluation reveals a significant performance gap between high-resource
languages~(such as English and French) and low-resource African languages. We
observe a significant performance gap between open and proprietary models, with
the highest performing open model, Gemma 2 27B only at 63% of the
best-performing proprietary model GPT-4o performance. In addition, machine
translating the test set to English before evaluation helped to close the gap
for larger models that are English-centric, such as Gemma 2 27B and LLaMa 3.1
70B. These findings suggest that more efforts are needed to develop and adapt
LLMs for African languages.
