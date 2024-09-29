---
layout: publication
title: "MBIAS: Mitigating Bias In Large Language Models While Retaining Context"
authors: Raza Shaina, Raval Ananya, Chatrath Veronica
conference: "Arxiv"
year: 2024
bibkey: raza2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11290"}
  - {name: "Code", url: "https://github.com/shainarazavi/MBIAS/tree/main"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
The deployment of Large Language Models (LLMs) in diverse applications necessitates an assurance of safety without compromising the contextual integrity of the generated content. Traditional approaches including safety-specific fine-tuning or adversarial testing often yield safe outputs at the expense of contextual meaning. This can result in a diminished capacity to handle nuanced aspects of bias and toxicity such as underrepresentation or negative portrayals across various demographics. To address these challenges we introduce MBIAS an LLM framework carefully instruction fine-tuned on a custom dataset designed specifically for safety interventions. MBIAS is designed to significantly reduce biases and toxic elements in LLM outputs while preserving the main information. This work also details our further use of LLMs as annotator under human supervision and as evaluator of generated content. Empirical analysis reveals that MBIAS achieves a reduction in bias and toxicity by over 3037; in standard evaluations and by more than 9037; in diverse demographic tests highlighting the robustness of our approach. We make the dataset and the fine-tuned model available to the research community for further investigation and ensure reproducibility. The code for this project can be accessed here https://github.com/shainarazavi/MBIAS/tree/main. Warning This paper contains examples that may be offensive or upsetting.
