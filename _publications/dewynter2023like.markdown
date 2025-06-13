---
layout: publication
title: '"i''d Like To Have An Argument, Please": Argumentative Reasoning In Large Language Models'
authors: Adrian De Wynter, Tangming Yuan
conference: "Arxiv"
year: 2023
bibkey: dewynter2023like
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16938"}
tags: ['Prompting', 'Applications', 'Reinforcement Learning']
---
We evaluate two large language models (LLMs) ability to perform argumentative
reasoning. We experiment with argument mining (AM) and argument pair extraction
(APE), and evaluate the LLMs' ability to recognize arguments under
progressively more abstract input and output (I/O) representations (e.g.,
arbitrary label sets, graphs, etc.). Unlike the well-known evaluation of prompt
phrasings, abstraction evaluation retains the prompt's phrasing but tests
reasoning capabilities. We find that scoring-wise the LLMs match or surpass the
SOTA in AM and APE, and under certain I/O abstractions LLMs perform well, even
beating chain-of-thought--we call this symbolic prompting. However, statistical
analysis on the LLMs outputs when subject to small, yet still human-readable,
alterations in the I/O representations (e.g., asking for BIO tags as opposed to
line numbers) showed that the models are not performing reasoning. This
suggests that LLM applications to some tasks, such as data labelling and paper
reviewing, must be done with care.
