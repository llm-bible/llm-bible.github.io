---
layout: publication
title: 'Question Decomposition Improves The Faithfulness Of Model-generated Reasoning'
authors: Ansh Radhakrishnan, Karina Nguyen, Anna Chen, Carol Chen, Carson Denison, Danny Hernandez, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė, Newton Cheng, Nicholas Joseph, Nicholas Schiefer, Oliver Rausch, Sam Mccandlish, Sheer El Showk, Tamera Lanham, Tim Maxwell, Venkatesa Chandrasekaran, Zac Hatfield-dodds, Jared Kaplan, Jan Brauner, Samuel R. Bowman, Ethan Perez
conference: "Arxiv"
year: 2023
bibkey: radhakrishnan2023question
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.11768'}
tags: ['Prompting', 'Responsible AI']
---
As large language models (LLMs) perform more difficult tasks, it becomes
harder to verify the correctness and safety of their behavior. One approach to
help with this issue is to prompt LLMs to externalize their reasoning, e.g., by
having them generate step-by-step reasoning as they answer a question
(Chain-of-Thought; CoT). The reasoning may enable us to check the process that
models use to perform tasks. However, this approach relies on the stated
reasoning faithfully reflecting the model's actual reasoning, which is not
always the case. To improve over the faithfulness of CoT reasoning, we have
models generate reasoning by decomposing questions into subquestions.
Decomposition-based methods achieve strong performance on question-answering
tasks, sometimes approaching that of CoT while improving the faithfulness of
the model's stated reasoning on several recently-proposed metrics. By forcing
the model to answer simpler subquestions in separate contexts, we greatly
increase the faithfulness of model-generated reasoning over CoT, while still
achieving some of the performance gains of CoT. Our results show it is possible
to improve the faithfulness of model-generated reasoning; continued
improvements may lead to reasoning that enables us to verify the correctness
and safety of LLM behavior.
