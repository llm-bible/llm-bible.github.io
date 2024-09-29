---
layout: publication
title: Iterative Graph Alignment
authors: Yu Fangyuan, Arora Hardeep Singh, Johnson Matt
conference: "Arxiv"
year: 2024
bibkey: yu2024iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16667"}
tags: ['Applications', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
By compressing diverse narratives LLMs go beyond memorization achieving intelligence by capturing generalizable causal relationships. However they suffer from local representation gaps due to insufficient training data diversity limiting their real45;world utility especially in tasks requiring strict alignment to rules. Traditional alignment methods relying on heavy human annotations are inefficient and unscalable. Recent self45;alignment techniques also fall short as they often depend on self45;selection based prompting and memorization45;based learning. To address these issues we introduce Iterative Graph Alignment (IGA) an annotation45;free rule45;based alignment algorithm. A teacher model (VLM) employs Iterative Graph Prompting (IGP) to create logical graphs and reference answers. The student model (LLM) identifies local knowledge gaps by attempting to align its responses with these references collaborating with helper models to generate diverse answers. These aligned responses are then used for iterative supervised fine45;tuning (SFT). Our evaluations across five rule45;based scenarios demonstrate IGPs effectiveness with a 73.1237; alignment improvement in Claude Sonnet 3.5 and Llama345;8B45;Instruct achieving an 86.2037; improvement outperforming Claude Sonnet 3.5 in rule45;based alignment.
