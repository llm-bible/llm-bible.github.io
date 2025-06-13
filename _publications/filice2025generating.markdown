---
layout: publication
title: 'Generating Diverse Q&A Benchmarks For RAG Evaluation With Datamorgana'
authors: Simone Filice, Guy Horowitz, David Carmel, Zohar Karnin, Liane Lewin-eytan, Yoelle Maarek
conference: "Arxiv"
year: 2025
bibkey: filice2025generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12789"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'SIGIR']
---
Evaluating Retrieval-Augmented Generation (RAG) systems, especially in
domain-specific contexts, requires benchmarks that address the distinctive
requirements of the applicative scenario. Since real data can be hard to
obtain, a common strategy is to use LLM-based methods to generate synthetic
data. Existing solutions are general purpose: given a document, they generate a
question to build a Q&A pair. However, although the generated questions can be
individually good, they are typically not diverse enough to reasonably cover
the different ways real end-users can interact with the RAG system. We
introduce here DataMorgana, a tool for generating highly customizable and
diverse synthetic Q&A benchmarks tailored to RAG applications. DataMorgana
enables detailed configurations of user and question categories and provides
control over their distribution within the benchmark. It uses a lightweight
two-stage process, ensuring efficiency and fast iterations, while generating
benchmarks that reflect the expected traffic. We conduct a thorough line of
experiments, showing quantitatively and qualitatively that DataMorgana
surpasses existing tools and approaches in producing lexically, syntactically,
and semantically diverse question sets across domain-specific and
general-knowledge corpora. DataMorgana will be made available to selected teams
in the research community, as first beta testers, in the context of the
upcoming SIGIR'2025 LiveRAG challenge to be announced in early February 2025.
