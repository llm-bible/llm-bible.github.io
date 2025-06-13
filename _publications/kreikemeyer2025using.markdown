---
layout: publication
title: 'Using (not So) Large Language Models For Generating Simulation Models In A Formal DSL -- A Study On Reaction Networks'
authors: Justin N. Kreikemeyer, Miłosz Jankowski, Pia Wilsdorf, Adelinde M. Uhrmacher
conference: "Arxiv"
year: 2025
bibkey: kreikemeyer2025using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01675"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Formal languages are an integral part of modeling and simulation. They allow the distillation of knowledge into concise simulation models amenable to automatic execution, interpretation, and analysis. However, the arguably most humanly accessible means of expressing models is through natural language, which is not easily interpretable by computers. Here, we evaluate how a Large Language Model (LLM) might be used for formalizing natural language into simulation models. Existing studies only explored using very large LLMs, like the commercial GPT models, without fine-tuning model weights. To close this gap, we show how an open-weights, 7B-parameter Mistral model can be fine-tuned to translate natural language descriptions to reaction network models in a domain-specific language, offering a self-hostable, compute-, and memory efficient alternative. To this end, we develop a synthetic data generator to serve as the basis for fine-tuning and evaluation. Our quantitative evaluation shows that our fine-tuned Mistral model can recover the ground truth simulation model in up to 84.5% of cases. In addition, our small-scale user study demonstrates the model's practical potential for one-time generation as well as interactive modeling in various domains. While promising, in its current form, the fine-tuned small LLM cannot catch up with large LLMs. We conclude that higher-quality training data are required, and expect future small and open-source LLMs to offer new opportunities.
