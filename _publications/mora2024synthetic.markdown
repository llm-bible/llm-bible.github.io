---
layout: publication
title: Synthetic Programming Elicitation and Repair for Text-to-Code in Very Low-Resource Programming Languages
authors: Mora Federico, Wong Justin, Lepe Haley, Bhatia Sahil, Elmaaroufi Karim, Varghese George, Gonzalez Joseph E., Polgreen Elizabeth, Seshia Sanjit A.
conference: "Arxiv"
year: 2024
bibkey: mora2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03636"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Recent advances in large language models (LLMs) for code applications have demonstrated remarkable zero-shot fluency and instruction following on challenging code related tasks ranging from test case generation to self-repair. Unsurprisingly however models struggle to compose syntactically valid programs in programming languages unrepresented in pre-training referred to as very low-resource Programming Languages (VLPLs). VLPLs appear in crucial settings including domain-specific languages for internal tools and tool-chains for legacy languages. Inspired by an HCI technique called natural program elicitation we propose designing an intermediate language that LLMs naturally know how to use and which can be automatically compiled to a target VLPL. When LLMs generate code that lies outside of this intermediate language we use compiler techniques to repair the code into programs in the intermediate language. Overall we introduce synthetic programming elicitation and compilation (SPEAC) an approach that enables LLMs to generate syntactically valid code even for VLPLs. We empirically evaluate the performance of SPEAC in a case study and find that compared to existing retrieval and fine-tuning baselines SPEAC produces syntactically correct programs significantly more frequently without sacrificing semantic correctness.
