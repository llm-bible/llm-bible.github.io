---
layout: publication
title: 'ASTRAL: Automated Safety Testing Of Large Language Models'
authors: Miriam Ugarte, Pablo Valle, José Antonio Parejo, Sergio Segura, Aitor Arrieta
conference: "The 6th ACM/IEEE International Conference on Automation of Software Test (AST 2025)"
year: 2025
bibkey: ugarte2025automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17132"}
tags: ['Responsible AI', 'Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'In-Context Learning', 'GPT', 'ACL', 'Prompting', 'Attention Mechanism']
---
Large Language Models (LLMs) have recently gained attention due to their
ability to understand and generate sophisticated human-like content. However,
ensuring their safety is paramount as they might provide harmful and unsafe
responses. Existing LLM testing frameworks address various safety-related
concerns (e.g., drugs, terrorism, animal abuse) but often face challenges due
to unbalanced and obsolete datasets. In this paper, we present ASTRAL, a tool
that automates the generation and execution of test cases (i.e., prompts) for
testing the safety of LLMs. First, we introduce a novel black-box coverage
criterion to generate balanced and diverse unsafe test inputs across a diverse
set of safety categories as well as linguistic writing characteristics (i.e.,
different style and persuasive writing techniques). Second, we propose an
LLM-based approach that leverages Retrieval Augmented Generation (RAG),
few-shot prompting strategies and web browsing to generate up-to-date test
inputs. Lastly, similar to current LLM test automation techniques, we leverage
LLMs as test oracles to distinguish between safe and unsafe test outputs,
allowing a fully automated testing approach. We conduct an extensive evaluation
on well-known LLMs, revealing the following key findings: i) GPT3.5 outperforms
other LLMs when acting as the test oracle, accurately detecting unsafe
responses, and even surpassing more recent LLMs (e.g., GPT-4), as well as LLMs
that are specifically tailored to detect unsafe LLM outputs (e.g., LlamaGuard);
ii) the results confirm that our approach can uncover nearly twice as many
unsafe LLM behaviors with the same number of test inputs compared to currently
used static datasets; and iii) our black-box coverage criterion combined with
web browsing can effectively guide the LLM on generating up-to-date unsafe test
inputs, significantly increasing the number of unsafe LLM behaviors.
