---
layout: publication
title: Biomedical Large Languages Models Seem Not To Be Superior To Generalist Models On Unseen Medical Data
authors: Dorfner Felix J., Dada Amin, Busch Felix, Makowski Marcus R., Han Tianyu, Truhn Daniel, Kleesiek Jens, Sushil Madhumita, Lammert Jacqueline, Adams Lisa C., Bressem Keno K.
conference: "Arxiv"
year: 2024
bibkey: dorfner2024biomedical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13833"}
tags: ['Applications', 'Language Modeling', 'Tools']
---
Large language models (LLMs) have shown potential in biomedical applications leading to efforts to fine45;tune them on domain45;specific data. However the effectiveness of this approach remains unclear. This study evaluates the performance of biomedically fine45;tuned LLMs against their general45;purpose counterparts on a variety of clinical tasks. We evaluated their performance on clinical case challenges from the New England Journal of Medicine (NEJM) and the Journal of the American Medical Association (JAMA) and on several clinical tasks (e.g. information extraction document summarization and clinical coding). Using benchmarks specifically chosen to be likely outside the fine45;tuning datasets of biomedical models we found that biomedical LLMs mostly perform inferior to their general45;purpose counterparts especially on tasks not focused on medical knowledge. While larger models showed similar performance on case tasks (e.g. OpenBioLLM45;70B 66.437; vs. Llama45;345;70B45;Instruct 6537; on JAMA cases) smaller biomedical models showed more pronounced underperformance (e.g. OpenBioLLM45;8B 3037; vs. Llama45;345;8B45;Instruct 64.337; on NEJM cases). Similar trends were observed across the CLUE (Clinical Language Understanding Evaluation) benchmark tasks with general45;purpose models often performing better on text generation question answering and coding tasks. Our results suggest that fine45;tuning LLMs to biomedical data may not provide the expected benefits and may potentially lead to reduced performance challenging prevailing assumptions about domain45;specific adaptation of LLMs and highlighting the need for more rigorous evaluation frameworks in healthcare AI. Alternative approaches such as retrieval45;augmented generation may be more effective in enhancing the biomedical capabilities of LLMs without compromising their general knowledge.
