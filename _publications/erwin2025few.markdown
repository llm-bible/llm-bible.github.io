---
layout: publication
title: 'Few-shot Policy (de)composition In Conversational Question Answering'
authors: Kyle Erwin, Guy Axelrod, Maria Chang, Achille Fokoue, Maxwell Crouse, Soham Dan, Tian Gao, Rosario Uceda-sosa, Ndivhuwo Makondo, Naweed Khan, Alexander Gray
conference: "Arxiv"
year: 2025
bibkey: erwin2025few
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.11335'}
tags: ['Interpretability and Explainability', 'Few-Shot', 'RAG', 'Model Architecture', 'Tools', 'Applications', 'Prompting', 'Ethics and Bias', 'Interpretability']
---
The task of policy compliance detection (PCD) is to determine if a scenario
is in compliance with respect to a set of written policies. In a conversational
setting, the results of PCD can indicate if clarifying questions must be asked
to determine compliance status. Existing approaches usually claim to have
reasoning capabilities that are latent or require a large amount of annotated
data. In this work, we propose logical decomposition for policy compliance
(LDPC): a neuro-symbolic framework to detect policy compliance using large
language models (LLMs) in a few-shot setting. By selecting only a few exemplars
alongside recently developed prompting techniques, we demonstrate that our
approach soundly reasons about policy compliance conversations by extracting
sub-questions to be answered, assigning truth values from contextual
information, and explicitly producing a set of logic statements from the given
policies. The formulation of explicit logic graphs can in turn help answer
PCDrelated questions with increased transparency and explainability. We apply
this approach to the popular PCD and conversational machine reading benchmark,
ShARC, and show competitive performance with no task-specific finetuning. We
also leverage the inherently interpretable architecture of LDPC to understand
where errors occur, revealing ambiguities in the ShARC dataset and highlighting
the challenges involved with reasoning for conversational question answering.
