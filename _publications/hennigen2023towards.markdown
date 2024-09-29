---
layout: publication
title: "Towards Verifiable Text Generation With Symbolic References"
authors: Hennigen Lucas Torroba, Shen Shannon, Nrusimha Aniruddha, Gapp Bernhard, Sontag David, Kim Yoon
conference: "Arxiv"
year: 2023
bibkey: hennigen2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09188"}
  - {name: "Code", url: "http://symgen.github.io"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Prompting', 'Reinforcement Learning']
---
LLMs are vulnerable to hallucinations and thus their outputs generally require laborious human verification for high-stakes applications. To this end we propose symbolically grounded generation (SymGen) as a simple approach for enabling easier manual validation of an LLMs output. SymGen prompts an LLM to interleave its regular output text with explicit symbolic references to fields present in some conditioning data (e.g. a table in JSON format). The references can be used to display the provenance of different spans of text in the generation reducing the effort required for manual verification. Across a range of data-to-text and question-answering experiments we find that LLMs are able to directly output text that makes use of accurate symbolic references while maintaining fluency and factuality. In a human study we further find that such annotations can streamline human verification of machine-generated text. Our code will be available at http://symgen.github.io."
