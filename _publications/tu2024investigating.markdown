---
layout: publication
title: 'Investigating Factuality In Long-form Text Generation: The Roles Of Self-known And Self-unknown'
authors: Lifu Tu, Rui Meng, Shafiq Joty, Yingbo Zhou, Semih Yavuz
conference: "Arxiv"
year: 2024
bibkey: tu2024investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.15993'}
tags: ['Language Modeling', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated strong capabilities in text
understanding and generation. However, they often lack factuality, producing a
mixture of true and false information, especially in long-form generation. In
this work, we investigates the factuality of long-form text generation across
various large language models (LLMs), including GPT-4, Gemini-1.5-Pro,
Claude-3-Opus, Llama-3-70B, and Mistral. Our analysis reveals that factuality
scores tend to decline in later sentences of the generated text, accompanied by
a rise in the number of unsupported claims. Furthermore, we explore the
effectiveness of different evaluation settings to assess whether LLMs can
accurately judge the correctness of their own outputs: Self-Known (the
percentage of supported atomic claims, decomposed from LLM outputs, that the
corresponding LLMs judge as correct) and Self-Unknown (the percentage of
unsupported atomic claims that the corresponding LLMs judge as incorrect). The
results indicate that even advanced models like GPT-4 and Gemini-1.5-Pro fail
to achieve perfect Self-Known scores, while their Self-Unknown scores remain
notably above zero, reflecting ongoing uncertainty in their self-assessments.
Moreover, we find a correlation between higher Self-Known scores and improved
factuality, while higher Self-Unknown scores are associated with lower
factuality. Interestingly, even without significant changes in the models'
self-judgment (Self-Known and Self-Unknown), the number of unsupported claims
can increases, likely as an artifact of long-form generation. These findings
show the limitations of current LLMs in long-form generation, and provide
valuable insights for improving factuality in long-form text generation.
