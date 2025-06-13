---
layout: publication
title: 'Medical Reasoning In Llms: An In-depth Analysis Of Deepseek R1'
authors: Birger Moell, Fredrik Sand Aronsson, Sanian Akbar
conference: "Arxiv"
year: 2025
bibkey: moell2025medical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00016'}
tags: ['Interpretability and Explainability', 'Applications', 'Tools', 'Fine-Tuning', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias']
---
Integrating large language models (LLMs) like DeepSeek R1 into healthcare
requires rigorous evaluation of their reasoning alignment with clinical
expertise. This study assesses DeepSeek R1's medical reasoning against expert
patterns using 100 MedQA clinical cases. The model achieved 93% diagnostic
accuracy, demonstrating systematic clinical judgment through differential
diagnosis, guideline-based treatment selection, and integration of
patient-specific factors. However, error analysis of seven incorrect cases
revealed persistent limitations: anchoring bias, challenges reconciling
conflicting data, insufficient exploration of alternatives, overthinking,
knowledge gaps, and premature prioritization of definitive treatment over
intermediate care. Crucially, reasoning length correlated with accuracy -
shorter responses (<5,000 characters) were more reliable, suggesting extended
explanations may signal uncertainty or rationalization of errors. While
DeepSeek R1 exhibits foundational clinical reasoning capabilities, recurring
flaws highlight critical areas for refinement, including bias mitigation,
knowledge updates, and structured reasoning frameworks. These findings
underscore LLMs' potential to augment medical decision-making through
artificial reasoning but emphasize the need for domain-specific validation,
interpretability safeguards, and confidence metrics (e.g., response length
thresholds) to ensure reliability in real-world applications.
