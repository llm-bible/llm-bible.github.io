---
layout: publication
title: 'Lost In The Logic: An Evaluation Of Large Language Models'' Reasoning Capabilities On LSAT Logic Games'
authors: Saumya Malik
conference: "Arxiv"
year: 2024
bibkey: malik2024lost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19012"}
tags: ['Tools', 'GPT', 'Prompting', 'Model Architecture']
---
In this thesis, I evaluate the performance of Large Language Models (LLMs) on
the Law School Admissions Test (LSAT), specifically the Logic Games section of
the test. I focus on this section because it presents a complex logical
reasoning task and thus is a valuable source of data for evaluating how modern,
increasingly capable LLMs can handle hard logical reasoning tasks. I construct
a dataset of LSAT logic games and their associated metadata, and extensively
evaluate LLMs' performance in a Chain-of-Thought prompting setting. Given the
weak performance in this setting, I explore other prompting frameworks on a
smaller subset of the dataset, adapting ideas from Reflexion to this task. This
results in a substantially improved accuracy of 70 percent for GPT-4 and 46
percent for GPT-3.5 on this data subset, highlighting the capacity of LLMs to
revise their logical errors, despite initially weak performance. Finally, I
analyze the types of logic games that models perform better or worse on, as
well as the types of logical errors I observe from human annotation, providing
detailed insights on the logical reasoning capabilities of LLMs.
