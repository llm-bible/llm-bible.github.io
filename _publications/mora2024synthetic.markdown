---
layout: publication
title: 'Synthetic Programming Elicitation For Text-to-code In Very Low-resource Programming And Formal Languages'
authors: Federico Mora, Justin Wong, Haley Lepe, Sahil Bhatia, Karim Elmaaroufi, George Varghese, Joseph E. Gonzalez, Elizabeth Polgreen, Sanjit A. Seshia
conference: "Arxiv"
year: 2024
bibkey: mora2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03636"}
tags: ['Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
Recent advances in large language models (LLMs) for code applications have
demonstrated remarkable zero-shot fluency and instruction following on
challenging code related tasks ranging from test case generation to
self-repair. Unsurprisingly, however, models struggle to compose syntactically
valid programs in programming languages unrepresented in pre-training, referred
to as very low-resource Programming Languages (VLPLs). VLPLs appear in crucial
settings, including domain-specific languages for internal tools, tool-chains
for legacy languages, and formal verification frameworks. Inspired by a
technique called natural programming elicitation, we propose designing an
intermediate language that LLMs "naturally" know how to use and which can be
automatically compiled to a target VLPL. When LLMs generate code that lies
outside of this intermediate language, we use compiler techniques to repair the
code into programs in the intermediate language. Overall, we introduce
*synthetic programming elicitation and compilation* (SPEAC), an approach
that enables LLMs to generate syntactically valid code even for VLPLs. We
empirically evaluate the performance of SPEAC in a case study for the UCLID5
formal verification language and find that, compared to existing retrieval and
fine-tuning baselines, SPEAC produces syntactically correct programs more
frequently and without sacrificing semantic correctness.
