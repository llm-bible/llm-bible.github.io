---
layout: publication
title: Learning To Deceive With Attention-based Explanations
authors: Pruthi Danish, Gupta Mansi, Dhingra Bhuwan, Neubig Graham, Lipton Zachary C.
conference: "Arxiv"
year: 2019
bibkey: pruthi2019learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.07913"}
tags: ['Attention Mechanism', 'Bias Mitigation', 'Ethics And Bias', 'Fairness', 'Interpretability And Explainability', 'Model Architecture', 'Responsible AI', 'Training Techniques', 'Transformer']
---
Attention mechanisms are ubiquitous components in neural architectures applied to natural language processing. In addition to yielding gains in predictive accuracy attention weights are often claimed to confer interpretability purportedly useful both for providing insights to practitioners and for explaining why a model makes its decisions to stakeholders. We call the latter use of attention mechanisms into question by demonstrating a simple method for training models to produce deceptive attention masks. Our method diminishes the total weight assigned to designated impermissible tokens even when the models can be shown to nevertheless rely on these features to drive predictions. Across multiple models and tasks our approach manipulates attention weights while paying surprisingly little cost in accuracy. Through a human study we show that our manipulated attention-based explanations deceive people into thinking that predictions from a model biased against gender minorities do not rely on the gender. Consequently our results cast doubt on attentions reliability as a tool for auditing algorithms in the context of fairness and accountability.
