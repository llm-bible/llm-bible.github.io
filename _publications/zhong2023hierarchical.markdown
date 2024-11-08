---
layout: publication
title: 'Hierarchical Neural Program Synthesis'
authors: Zhong Linghan, Lindeborg Ryan, Zhang Jesse, Lim Joseph J., Sun Shao-hua
conference: "Arxiv"
year: 2023
bibkey: zhong2023hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.06018"}
  - {name: "Code", url: "https://thoughtp0lice.github.io/hnps_web/"}
tags: ['Agentic', 'Has Code', 'RAG', 'Tools']
---
Program synthesis aims to automatically construct human-readable programs
that satisfy given task specifications, such as input/output pairs or
demonstrations. Recent works have demonstrated encouraging results in a variety
of domains, such as string transformation, tensor manipulation, and describing
behaviors of embodied agents. Most existing program synthesis methods are
designed to synthesize programs from scratch, generating a program token by
token, line by line. This fundamentally prevents these methods from scaling up
to synthesize programs that are longer or more complex. In this work, we
present a scalable program synthesis framework that instead synthesizes a
program by hierarchically composing programs. Specifically, we first learn a
task embedding space and a program decoder that can decode a task embedding
into a program. Then, we train a high-level module to comprehend the task
specification (e.g., input/output pairs or demonstrations) from long programs
and produce a sequence of task embeddings, which are then decoded by the
program decoder and composed to yield the synthesized program. We extensively
evaluate our proposed framework in a string transformation domain with
input/output pairs. The experimental results demonstrate that the proposed
framework can synthesize programs that are significantly longer and more
complex than the programs considered in prior program synthesis works. Website
at https://thoughtp0lice.github.io/hnps_web/
