---
layout: publication
title: 'Revealing And Reducing Gender Biases In Vision And Language Assistants (vlas)'
authors: Leander Girrbach, Stephan Alaniz, Yiran Huang, Trevor Darrell, Zeynep Akata
conference: "Arxiv"
year: 2024
bibkey: girrbach2024revealing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19314"}
  - {name: "Code", url: "https://github.com/ExplainableML/vla-gender-bias"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Pre-trained large language models (LLMs) have been reliably integrated with
visual input for multimodal tasks. The widespread adoption of instruction-tuned
image-to-text vision-language assistants (VLAs) like LLaVA and InternVL
necessitates evaluating gender biases. We study gender bias in 22 popular
open-source VLAs with respect to personality traits, skills, and occupations.
Our results show that VLAs replicate human biases likely present in the data,
such as real-world occupational imbalances. Similarly, they tend to attribute
more skills and positive personality traits to women than to men, and we see a
consistent tendency to associate negative personality traits with men. To
eliminate the gender bias in these models, we find that fine-tuning-based
debiasing methods achieve the best trade-off between debiasing and retaining
performance on downstream tasks. We argue for pre-deploying gender bias
assessment in VLAs and motivate further development of debiasing strategies to
ensure equitable societal outcomes. Code is available at
https://github.com/ExplainableML/vla-gender-bias.
