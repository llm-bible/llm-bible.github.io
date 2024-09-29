---
layout: publication
title: Prompting Techniques For Secure Code Generation A Systematic Investigation
authors: Tony Catherine, Ferreyra Nicolás E. Díaz, Mutas Markus, Dhiff Salem, Scandariato Riccardo
conference: "Arxiv"
year: 2024
bibkey: tony2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07064"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Security', 'Survey Paper']
---
Large Language Models (LLMs) are gaining momentum in software development with prompt-driven programming enabling developers to create code from natural language (NL) instructions. However studies have questioned their ability to produce secure code and thereby the quality of prompt-generated software. Alongside various prompting techniques that carefully tailor prompts have emerged to elicit optimal responses from LLMs. Still the interplay between such prompting strategies and secure code generation remains under-explored and calls for further investigations. OBJECTIVE In this study we investigate the impact of different prompting techniques on the security of code generated from NL instructions by LLMs. METHOD First we perform a systematic literature review to identify the existing prompting techniques that can be used for code generation tasks. A subset of these techniques are evaluated on GPT-3 GPT-3.5 and GPT-4 models for secure code generation. For this we used an existing dataset consisting of 150 NL security-relevant code-generation prompts. RESULTS Our work (i) classifies potential prompting techniques for code generation (ii) adapts and evaluates a subset of the identified techniques for secure code generation tasks and (iii) observes a reduction in security weaknesses across the tested LLMs especially after using an existing technique called Recursive Criticism and Improvement (RCI) contributing valuable insights to the ongoing discourse on LLM-generated code security.
