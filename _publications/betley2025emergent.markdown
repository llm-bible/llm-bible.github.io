---
layout: publication
title: 'Emergent Misalignment: Narrow Finetuning Can Produce Broadly Misaligned Llms'
authors: Jan Betley, Daniel Tan, Niels Warncke, Anna Sztyber-betley, Xuchan Bao, Martín Soto, Nathan Labenz, Owain Evans
conference: "Arxiv"
year: 2025
bibkey: betley2025emergent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17424"}
tags: ['GPT', 'Interpretability and Explainability', 'Model Architecture', 'Security', 'Training Techniques', 'Prompting']
---
We present a surprising result regarding LLMs and alignment. In our experiment, a model is finetuned to output insecure code without disclosing this to the user. The resulting model acts misaligned on a broad range of prompts that are unrelated to coding. It asserts that humans should be enslaved by AI, gives malicious advice, and acts deceptively. Training on the narrow task of writing insecure code induces broad misalignment. We call this emergent misalignment. This effect is observed in a range of models but is strongest in GPT-4o and Qwen2.5-Coder-32B-Instruct. Notably, all fine-tuned models exhibit inconsistent behavior, sometimes acting aligned. Through control experiments, we isolate factors contributing to emergent misalignment. Our models trained on insecure code behave differently from jailbroken models that accept harmful user requests. Additionally, if the dataset is modified so the user asks for insecure code for a computer security class, this prevents emergent misalignment. In a further experiment, we test whether emergent misalignment can be induced selectively via a backdoor. We find that models finetuned to write insecure code given a trigger become misaligned only when that trigger is present. So the misalignment is hidden without knowledge of the trigger. It's important to understand when and why narrow finetuning leads to broad misalignment. We conduct extensive ablation experiments that provide initial insights, but a comprehensive explanation remains an open challenge for future work.
