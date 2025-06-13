---
layout: publication
title: 'Privacy Policy Analysis Through Prompt Engineering For Llms'
authors: Arda Goknil, Femke B. Gelderblom, Simeon Tverdal, Shukun Tokas, Hui Song
conference: "Arxiv"
year: 2024
bibkey: goknil2024privacy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14879'}
tags: ['Few-Shot', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'GPT', 'Prompting', 'Ethics and Bias', 'Interpretability']
---
Privacy policies are often obfuscated by their complexity, which impedes
transparency and informed consent. Conventional machine learning approaches for
automatically analyzing these policies demand significant resources and
substantial domain-specific training, causing adaptability issues. Moreover,
they depend on extensive datasets that may require regular maintenance due to
changing privacy concerns.
  In this paper, we propose, apply, and assess PAPEL (Privacy Policy Analysis
through Prompt Engineering for LLMs), a framework harnessing the power of Large
Language Models (LLMs) through prompt engineering to automate the analysis of
privacy policies. PAPEL aims to streamline the extraction, annotation, and
summarization of information from these policies, enhancing their accessibility
and comprehensibility without requiring additional model training. By
integrating zero-shot, one-shot, and few-shot learning approaches and the
chain-of-thought prompting in creating predefined prompts and prompt templates,
PAPEL guides LLMs to efficiently dissect, interpret, and synthesize the
critical aspects of privacy policies into user-friendly summaries. We
demonstrate the effectiveness of PAPEL with two applications: (i) annotation
and (ii) contradiction analysis. We assess the ability of several LLaMa and GPT
models to identify and articulate data handling practices, offering insights
comparable to existing automated analysis approaches while reducing training
efforts and increasing the adaptability to new analytical needs. The
experiments demonstrate that the LLMs PAPEL utilizes (LLaMA and Chat GPT
models) achieve robust performance in privacy policy annotation, with F1 scores
reaching 0.8 and above (using the OPP-115 gold standard), underscoring the
effectiveness of simpler prompts across various advanced language models.
