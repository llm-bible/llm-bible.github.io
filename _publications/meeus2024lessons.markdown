---
layout: publication
title: 'Chocollama: Lessons Learned From Teaching Llamas Dutch'
authors: Matthieu Meeus, Anthony Rathé, François Remy, Pieter Delobelle, Jens-joris Decorte, Thomas Demeester
conference: "Arxiv"
year: 2024
bibkey: meeus2024lessons
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07633"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
While Large Language Models (LLMs) have shown remarkable capabilities in
natural language understanding and generation, their performance often lags in
lower-resource, non-English languages due to biases in the training data. In
this work, we explore strategies for adapting the primarily English LLMs
(Llama-2 and Llama-3) to Dutch, a language spoken by 30 million people
worldwide yet often underrepresented in LLM development. We collect 104GB of
Dutch text (\\(32\\)B tokens) from various sources to first apply continued
pretraining using low-rank adaptation (LoRA), complemented with Dutch
posttraining strategies provided by prior work. For Llama-2, we consider using
(i) the tokenizer of the original model, and (ii) training a new,
Dutch-specific tokenizer combined with embedding reinitialization. We evaluate
our adapted models, ChocoLlama-2, both on standard benchmarks and a novel Dutch
benchmark, ChocoLlama-Bench. Our results demonstrate that LoRA can effectively
scale for language adaptation, and that tokenizer modification with careful
weight reinitialization can improve performance. Notably, Llama-3 was released
during the course of this project and, upon evaluation, demonstrated superior
Dutch capabilities compared to our Dutch-adapted versions of Llama-2. We hence
apply the same adaptation technique to Llama-3, using its original tokenizer.
While our adaptation methods enhanced Llama-2's Dutch capabilities, we found
limited gains when applying the same techniques to Llama-3. This suggests that
for ever improving, multilingual foundation models, language adaptation
techniques may benefit more from focusing on language-specific posttraining
rather than on continued pretraining. We hope this work contributes to the
broader understanding of adapting LLMs to lower-resource languages, and to the
development of Dutch LLMs in particular.
