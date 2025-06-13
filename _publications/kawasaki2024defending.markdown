---
layout: publication
title: 'Defending Large Language Models Against Attacks With Residual Stream Activation Analysis'
authors: Amelia Kawasaki, Andrew Davis, Houssam Abbas
conference: "Arxiv"
year: 2024
bibkey: kawasaki2024defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03230"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Prompting']
---
The widespread adoption of Large Language Models (LLMs), exemplified by
OpenAI's ChatGPT, brings to the forefront the imperative to defend against
adversarial threats on these models. These attacks, which manipulate an LLM's
output by introducing malicious inputs, undermine the model's integrity and the
trust users place in its outputs. In response to this challenge, our paper
presents an innovative defensive strategy, given white box access to an LLM,
that harnesses residual activation analysis between transformer layers of the
LLM. We apply a novel methodology for analyzing distinctive activation patterns
in the residual streams for attack prompt classification. We curate multiple
datasets to demonstrate how this method of classification has high accuracy
across multiple types of attack scenarios, including our newly-created attack
dataset. Furthermore, we enhance the model's resilience by integrating safety
fine-tuning techniques for LLMs in order to measure its effect on our
capability to detect attacks. The results underscore the effectiveness of our
approach in enhancing the detection and mitigation of adversarial inputs,
advancing the security framework within which LLMs operate.
