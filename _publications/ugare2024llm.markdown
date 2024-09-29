---
layout: publication
title: Syncode LLM Generation With Grammar Augmentation
authors: Ugare Shubham, Suresh Tarun, Kang Hangoo, Misailovic Sasa, Singh Gagandeep
conference: "Arxiv"
year: 2024
bibkey: ugare2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01632"}
  - {name: "Code", url: "https://github.com/uiuc&#45;focal&#45;lab/syncode"}
tags: ['Applications', 'Has Code', 'Tools']
---
LLMs are widely used in complex AI applications. These applications underscore the need for LLM outputs to adhere to a specific format for their integration with other components in the systems. Typically the format rules e.g. for data serialization formats such as JSON YAML or Code in Programming Language are expressed as context45;free grammar (CFG). Due to the hallucinations and unreliability of LLMs instructing LLMs to adhere to specified syntax becomes an increasingly important challenge. We present SynCode a novel framework for efficient and general syntactical decoding with LLMs to address this challenge. SynCode ensures soundness and completeness with respect to the CFG of a formal language effectively retaining valid tokens while filtering out invalid ones. SynCode uses an offline45;constructed efficient lookup table the DFA mask store derived from the DFA of the languages grammar for efficient generation. SynCode seamlessly integrates with any language defined by CFG as evidenced by experiments focusing on generating JSON Python and Go outputs. Our experiments evaluating the effectiveness of SynCode for JSON generation demonstrate that SynCode eliminates all syntax errors and significantly outperforms state45;of45;the45;art baselines. Furthermore our results underscore how SynCode significantly reduces 96.0737; of syntax errors in generated Python and Go code showcasing its substantial impact on enhancing syntactical precision in LLM generation. Our code is available at https://github.com/uiuc&#45;focal&#45;lab/syncode
