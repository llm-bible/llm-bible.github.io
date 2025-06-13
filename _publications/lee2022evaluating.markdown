---
layout: publication
title: 'Evaluating Human-language Model Interaction'
authors: Mina Lee, Megha Srivastava, Amelia Hardy, John Thickstun, Esin Durmus, Ashwin Paranjape, Ines Gerard-ursin, Xiang Lisa Li, Faisal Ladhak, Frieda Rong, Rose E. Wang, Minae Kwon, Joon Sung Park, Hancheng Cao, Tony Lee, Rishi Bommasani, Michael Bernstein, Percy Liang
conference: "Arxiv"
year: 2022
bibkey: lee2022evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.09746'}
tags: ['GPT', 'Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Many real-world applications of language models (LMs), such as writing
assistance and code autocomplete, involve human-LM interaction. However, most
benchmarks are non-interactive in that a model produces output without human
involvement. To evaluate human-LM interaction, we develop a new framework,
Human-AI Language-based Interaction Evaluation (HALIE), that defines the
components of interactive systems and dimensions to consider when designing
evaluation metrics. Compared to standard, non-interactive evaluation, HALIE
captures (i) the interactive process, not only the final output; (ii) the
first-person subjective experience, not just a third-party assessment; and
(iii) notions of preference beyond quality (e.g., enjoyment and ownership). We
then design five tasks to cover different forms of interaction: social
dialogue, question answering, crossword puzzles, summarization, and metaphor
generation. With four state-of-the-art LMs (three variants of OpenAI's GPT-3
and AI21 Labs' Jurassic-1), we find that better non-interactive performance
does not always translate to better human-LM interaction. In particular, we
highlight three cases where the results from non-interactive and interactive
metrics diverge and underscore the importance of human-LM interaction for LM
evaluation.
