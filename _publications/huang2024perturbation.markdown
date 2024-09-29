---
layout: publication
title: Vaccine Perturbation45;aware Alignment For Large Language Models Against Harmful Fine45;tuning
authors: Huang Tiansheng, Hu Sihao, Liu Ling
conference: "Arxiv"
year: 2024
bibkey: huang2024perturbation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01109"}
  - {name: "Code", url: "https://github.com/git&#45;disl/Vaccine&#125;"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security']
---
The new paradigm of finetuning45;as45;a45;service introduces a new attack surface for Large Language Models (LLMs) a few harmful data uploaded by users can easily trick the finetuning to produce an alignment45;broken model. We conduct an empirical analysis and uncover a textit123;harmful embedding drift125; phenomenon showing a probable cause of the alignment45;broken effect. Inspired by our findings we propose Vaccine a perturbation45;aware alignment technique to mitigate the security risk of users finetuning. The core idea of Vaccine is to produce invariant hidden embeddings by progressively adding crafted perturbation to them in the alignment phase. This enables the embeddings to withstand harmful perturbation from un45;sanitized user data in the finetuning phase. Our results on open source mainstream LLMs (e.g. Llama2 Opt Vicuna) demonstrate that Vaccine can boost the robustness of alignment against harmful prompts induced embedding drift while reserving reasoning ability towards benign prompts. Our code is available at url123;https://github.com/git&#45;disl/Vaccine&#125;.
