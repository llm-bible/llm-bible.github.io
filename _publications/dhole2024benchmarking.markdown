---
layout: publication
title: 'Conqret: Benchmarking Fine-grained Evaluation Of Retrieval Augmented Argumentation With LLM Judges'
authors: Kaustubh D. Dhole, Kai Shu, Eugene Agichtein
conference: "Arxiv"
year: 2024
bibkey: dhole2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05206"}
tags: ['RAG', 'Tools', 'Reinforcement Learning']
---
Computational argumentation, which involves generating answers or summaries
for controversial topics like abortion bans and vaccination, has become
increasingly important in today's polarized environment. Sophisticated LLM
capabilities offer the potential to provide nuanced, evidence-based answers to
such questions through Retrieval-Augmented Argumentation (RAArg), leveraging
real-world evidence for high-quality, grounded arguments. However, evaluating
RAArg remains challenging, as human evaluation is costly and difficult for
complex, lengthy answers on complicated topics. At the same time, re-using
existing argumentation datasets is no longer sufficient, as they lack long,
complex arguments and realistic evidence from potentially misleading sources,
limiting holistic evaluation of retrieval effectiveness and argument quality.
To address these gaps, we investigate automated evaluation methods using
multiple fine-grained LLM judges, providing better and more interpretable
assessments than traditional single-score metrics and even previously reported
human crowdsourcing. To validate the proposed techniques, we introduce ConQRet,
a new benchmark featuring long and complex human-authored arguments on debated
topics, grounded in real-world websites, allowing an exhaustive evaluation
across retrieval effectiveness, argument quality, and groundedness. We validate
our LLM Judges on a prior dataset and the new ConQRet benchmark. Our proposed
LLM Judges and the ConQRet benchmark can enable rapid progress in computational
argumentation and can be naturally extended to other complex
retrieval-augmented generation tasks.
