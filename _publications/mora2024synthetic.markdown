---
layout: publication
title: Synthetic Programming Elicitation And Repair For Text45;to45;code In Very Low45;resource Programming Languages
authors: Mora Federico, Wong Justin, Lepe Haley, Bhatia Sahil, Elmaaroufi Karim, Varghese George, Gonzalez Joseph E., Polgreen Elizabeth, Seshia Sanjit A.
conference: "Arxiv"
year: 2024
bibkey: mora2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03636"}
tags: ['Applications', 'Tools', 'Training Techniques']
---
Recent advances in large language models (LLMs) for code applications have demonstrated remarkable zero45;shot fluency and instruction following on challenging code related tasks ranging from test case generation to self45;repair. Unsurprisingly however models struggle to compose syntactically valid programs in programming languages unrepresented in pre45;training referred to as very low45;resource Programming Languages (VLPLs). VLPLs appear in crucial settings including domain45;specific languages for internal tools and tool45;chains for legacy languages. Inspired by an HCI technique called natural program elicitation we propose designing an intermediate language that LLMs naturally know how to use and which can be automatically compiled to a target VLPL. When LLMs generate code that lies outside of this intermediate language we use compiler techniques to repair the code into programs in the intermediate language. Overall we introduce emph123;synthetic programming elicitation and compilation125; (SPEAC) an approach that enables LLMs to generate syntactically valid code even for VLPLs. We empirically evaluate the performance of SPEAC in a case study and find that compared to existing retrieval and fine45;tuning baselines SPEAC produces syntactically correct programs significantly more frequently without sacrificing semantic correctness.
