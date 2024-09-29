---
layout: publication
title: Aligning Model Evaluations With Human Preferences&#58; Mitigating Token Count Bias In Language Model Assessments
authors: Daynauth Roland, Mars Jason
conference: "Arxiv"
year: 2024
bibkey: daynauth2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12847"}
tags: ['Applications', 'Bias Mitigation', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
The SLAM paper demonstrated that on-device Small Language Models (SLMs) are a viable and cost-effective alternative to API-based Large Language Models (LLMs) such as OpenAIs GPT-4 offering comparable performance and stability. However SLAM also identified discrepancies between human preferences and traditional auto-evaluators. This follow-up paper explores methods to align LLM evaluator preferences with human evaluations by addressing biases particularly toward higher token counts. We employed Bayesian statistics and a t-test to quantify this bias and developed a recalibration procedure to adjust the GPTScorer. Our findings significantly improve aligning the recalibrated LLM evaluator with human evaluations across multiple use cases. For instance spearmans ranking correlation score in the Recommendation use case improved from -27.27 to 44.55. These results highlight the importance of accounting for biases in automated evaluations to ensure fair and accurate model assessments. The recalibration process enhances the reliability of automated evaluators leading to better AI models that align with human values and expectations. This study provides a robust methodology for future research into bias correction and emphasizes the feasibility and benefits of developing human-aligned AI evaluation systems.
