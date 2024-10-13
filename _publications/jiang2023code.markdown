---
layout: publication
title: 'Selfevolve: A Code Evolution Framework Via Large Language Models'
authors: Jiang Shuyang, Wang Yuhao, Wang Yu
conference: "Arxiv"
year: 2023
bibkey: jiang2023code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.02907"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Large language models (LLMs) have already revolutionized code generation,
after being pretrained on publicly available code data. However, while various
methods have been proposed to augment LLMs with retrieved knowledge and enhance
the quality of code generation, the performance of these retrieval-based
methods is limited by the strength of the retrievers used. In addition, while
LLMs show great emergent ability, they still struggle to produce the correct
code in one turn. To address these challenges, we propose a novel two-step
pipeline, called \autoknow, that leverages LLMs as both knowledge providers and
self-reflective programmers. Unlike retrieval-based methods, \autoknow~obtains
the knowledge from input prompts and generates intermediate code based on the
generated knowledge. After that, \autoknow~asks LLM to act as an expert
programmer to perform debugging for the generated code. This is achieved by
receiving the error message from the interpreter, without requiring special
test cases for correctness verification. We evaluate \autoknow~on three code
generation datasets, including DS-1000 for data science code, HumanEval for
software engineering code, and TransCoder for C++-to-Python translation. Our
empirical experiments show that \autoknow~outperforms strong baselines by a
significant margin on all datasets. We also conduct exhaustive analytical
experiments to validate the effectiveness of the two stages of \autoknow, and
find that both are superior to other prompting-based methods. Further
scalability analysis demonstrates that \autoknow~can be adapted to other more
advanced models, such as GPT-4, and bring consistent efficacy improvement.
