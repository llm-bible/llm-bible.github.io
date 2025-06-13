---
layout: publication
title: 'New Evaluation Paradigm For Lexical Simplification'
authors: Jipeng Qiang, Minjiang Huang, Yi Zhu, Yunhao Yuan, Chaowei Zhang, Xiaoye Ouyang
conference: "Arxiv"
year: 2025
bibkey: qiang2025new
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.15268'}
tags: ['Prompting', 'In-Context Learning']
---
Lexical Simplification (LS) methods use a three-step pipeline: complex word
identification, substitute generation, and substitute ranking, each with
separate evaluation datasets. We found large language models (LLMs) can
simplify sentences directly with a single prompt, bypassing the traditional
pipeline. However, existing LS datasets are not suitable for evaluating these
LLM-generated simplified sentences, as they focus on providing substitutes for
single complex words without identifying all complex words in a sentence.
  To address this gap, we propose a new annotation method for constructing an
all-in-one LS dataset through human-machine collaboration. Automated methods
generate a pool of potential substitutes, which human annotators then assess,
suggesting additional alternatives as needed. Additionally, we explore
LLM-based methods with single prompts, in-context learning, and
chain-of-thought techniques. We introduce a multi-LLMs collaboration approach
to simulate each step of the LS task. Experimental results demonstrate that LS
based on multi-LLMs approaches significantly outperforms existing baselines.
