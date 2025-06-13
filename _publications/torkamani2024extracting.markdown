---
layout: publication
title: 'Kajal: Extracting Grammar Of A Source Code Using Large Language Models'
authors: Mohammad Jalili Torkamani
conference: "Arxiv"
year: 2024
bibkey: torkamani2024extracting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08842'}
tags: ['Few-Shot', 'RAG', 'Prompting']
---
Understanding and extracting the grammar of a domain-specific language (DSL)
is crucial for various software engineering tasks; however, manually creating
these grammars is time-intensive and error-prone. This paper presents Kajal, a
novel approach that automatically infers grammar from DSL code snippets by
leveraging Large Language Models (LLMs) through prompt engineering and few-shot
learning. Kajal dynamically constructs input prompts, using contextual
information to guide the LLM in generating the corresponding grammars, which
are iteratively refined through a feedback-driven approach. Our experiments
show that Kajal achieves 60% accuracy with few-shot learning and 45% without
it, demonstrating the significant impact of few-shot learning on the tool's
effectiveness. This approach offers a promising solution for automating DSL
grammar extraction, and future work will explore using smaller, open-source
LLMs and testing on larger datasets to further validate Kajal's performance.
