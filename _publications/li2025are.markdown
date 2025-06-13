---
layout: publication
title: 'Are Llms Reliable Translators Of Logical Reasoning Across Lexically Diversified Contexts?'
authors: Qingchuan Li, Jiatong Li, Zirui Liu, Mingyue Cheng, Yuting Zeng, Qi Liu, Tongxuan Liu
conference: "Arxiv"
year: 2025
bibkey: li2025are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04575"}
  - {name: "Code", url: "https://github.com/wufeiwuwoshihua/LexicalDiver"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'In-Context Learning']
---
Neuro-symbolic approaches combining large language models (LLMs) with solvers excels in logical reasoning problems need long reasoning chains. In this paradigm, LLMs serve as translators, converting natural language reasoning problems into formal logic formulas. Then reliable symbolic solvers return correct solutions. Despite their success, we find that LLMs, as translators, struggle to handle lexical diversification, a common linguistic phenomenon, indicating that LLMs as logic translators are unreliable in real-world scenarios. Moreover, existing logical reasoning benchmarks lack lexical diversity, failing to challenge LLMs' ability to translate such text and thus obscuring this issue. In this work, we propose SCALe, a benchmark designed to address this significant gap through **logic-invariant lexical diversification**. By using LLMs to transform original benchmark datasets into lexically diversified but logically equivalent versions, we evaluate LLMs' ability to consistently map diverse expressions to uniform logical symbols on these new datasets. Experiments using SCALe further confirm that current LLMs exhibit deficiencies in this capability. Building directly on the deficiencies identified through our benchmark, we propose a new method, MenTaL, to address this limitation. This method guides LLMs to first construct a table unifying diverse expressions before performing translation. Applying MenTaL through in-context learning and supervised fine-tuning (SFT) significantly improves the performance of LLM translators on lexically diversified text. Our code is now available at https://github.com/wufeiwuwoshihua/LexicalDiver.
