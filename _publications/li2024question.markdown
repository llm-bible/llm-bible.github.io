---
layout: publication
title: 'MEDIQ: Question-asking Llms For Adaptive And Reliable Clinical Reasoning'
authors: Li Shuyue Stella, Balachandran Vidhisha, Feng Shangbin, Ilgen Jonathan, Pierson Emma, Koh Pang Wei, Tsvetkov Yulia
conference: "Arxiv"
year: 2024
bibkey: li2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00922"}
tags: ['Applications', 'Prompting', 'TACL', 'Tools']
---
In high-stakes domains like clinical reasoning, AI assistants powered by
large language models (LLMs) are yet to be reliable and safe. We identify a key
obstacle towards reliability: existing LLMs are trained to answer any question,
even with incomplete context in the prompt or insufficient parametric
knowledge. We propose to change this paradigm to develop more careful LLMs that
ask follow-up questions to gather necessary and sufficient information and
respond reliably. We introduce MEDIQ, a framework to simulate realistic
clinical interactions, which incorporates a Patient System and an adaptive
Expert System. The Patient may provide incomplete information in the beginning;
the Expert refrains from making diagnostic decisions when unconfident, and
instead elicits missing details from the Patient via follow-up questions. To
evaluate MEDIQ, we convert MEDQA and CRAFT-MD -- medical benchmarks for
diagnostic question answering -- into an interactive setup. We develop a
reliable Patient system and prototype several Expert systems, first showing
that directly prompting state-of-the-art LLMs to ask questions degrades the
quality of clinical reasoning, indicating that adapting LLMs to interactive
information-seeking settings is nontrivial. We then augment the Expert with a
novel abstention module to better estimate model confidence and decide whether
to ask more questions, thereby improving diagnostic accuracy by 20.3%; however,
performance still lags compared to an (unrealistic in practice) upper bound
when full information is given upfront. Further analyses reveal that
interactive performance can be improved by filtering irrelevant contexts and
reformatting conversations. Overall, our paper introduces a novel problem
towards LLM reliability, a novel MEDIQ framework, and highlights important
future directions to extend the information-seeking abilities of LLM assistants
in critical domains.
