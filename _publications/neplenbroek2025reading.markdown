---
layout: publication
title: 'Reading Between The Prompts: How Stereotypes Shape Llm''s Implicit Personalization'
authors: Vera Neplenbroek, Arianna Bisazza, Raquel Fernández
conference: "Arxiv"
year: 2025
bibkey: neplenbroek2025reading
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16467'}
tags: ['Ethics and Bias', 'Interpretability', 'Prompting']
---
Generative Large Language Models (LLMs) infer user's demographic information from subtle cues in the conversation -- a phenomenon called implicit personalization. Prior work has shown that such inferences can lead to lower quality responses for users assumed to be from minority groups, even when no demographic information is explicitly provided. In this work, we systematically explore how LLMs respond to stereotypical cues using controlled synthetic conversations, by analyzing the models' latent user representations through both model internals and generated answers to targeted user questions. Our findings reveal that LLMs do infer demographic attributes based on these stereotypical signals, which for a number of groups even persists when the user explicitly identifies with a different demographic group. Finally, we show that this form of stereotype-driven implicit personalization can be effectively mitigated by intervening on the model's internal representations using a trained linear probe to steer them toward the explicitly stated identity. Our results highlight the need for greater transparency and control in how LLMs represent user identity.
