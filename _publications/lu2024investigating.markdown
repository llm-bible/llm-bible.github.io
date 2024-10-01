---
layout: publication
title: 'Investigating Bias Representations In Llama 2 Chat Via Activation Steering'
authors: Lu Dawn, Rimsky Nina
conference: "Arxiv"
year: 2024
bibkey: lu2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00402"}
tags: ['Agentic', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
We address the challenge of societal bias in Large Language Models (LLMs), focusing on the Llama 2 7B Chat model. As LLMs are increasingly integrated into decision-making processes with substantial societal impact, it becomes imperative to ensure these models do not reinforce existing biases. Our approach employs activation steering to probe for and mitigate biases related to gender, race, and religion. This method manipulates model activations to direct responses towards or away from biased outputs, utilizing steering vectors derived from the StereoSet dataset and custom GPT4 generated gender bias prompts. Our findings reveal inherent gender bias in Llama 2 7B Chat, persisting even after Reinforcement Learning from Human Feedback (RLHF). We also observe a predictable negative correlation between bias and the model's tendency to refuse responses. Significantly, our study uncovers that RLHF tends to increase the similarity in the model's representation of different forms of societal biases, which raises questions about the model's nuanced understanding of different forms of bias. This work also provides valuable insights into effective red-teaming strategies for LLMs using activation steering, particularly emphasizing the importance of integrating a refusal vector.
