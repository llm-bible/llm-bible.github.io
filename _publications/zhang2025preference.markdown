---
layout: publication
title: 'Preference Learning Unlocks Llms'' Psycho-counseling Skills'
authors: Mian Zhang, Shaun M. Eack, Zhiyu Zoey Chen
conference: "Arxiv"
year: 2025
bibkey: zhang2025preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19731"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques']
---
Applying large language models (LLMs) to assist in psycho-counseling is an
emerging and meaningful approach, driven by the significant gap between patient
needs and the availability of mental health support. However, current LLMs
struggle to consistently provide effective responses to client speeches,
largely due to the lack of supervision from high-quality real psycho-counseling
data, whose content is typically inaccessible due to client privacy concerns.
Furthermore, the quality of therapists' responses in available sessions can
vary significantly based on their professional training and experience.
Assessing the quality of therapists' responses remains an open challenge. In
this work, we address these challenges by first proposing a set of professional
and comprehensive principles to evaluate therapists' responses to client
speeches. Using these principles, we create a preference dataset,
PsychoCounsel-Preference, which contains 36k high-quality preference comparison
pairs. This dataset aligns with the preferences of professional
psychotherapists, providing a robust foundation for evaluating and improving
LLMs in psycho-counseling. Experiments on reward modeling and preference
learning demonstrate that PsychoCounsel-Preference is an excellent resource for
LLMs to acquire essential skills for responding to clients in a counseling
session. Our best-aligned model, PsychoCounsel-Llama3-8B, achieves an
impressive win rate of 87% against GPT-4o. We release PsychoCounsel-Preference,
PsychoCounsel-Llama3-8B and the reward model PsychoCounsel Llama3-8B-Reward to
facilitate the research of psycho-counseling with LLMs at:
https://hf.co/Psychotherapy-LLM.
