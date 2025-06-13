---
layout: publication
title: 'Could AI Trace And Explain The Origins Of Ai-generated Images And Text?'
authors: Hongchao Fang, Yixin Liu, Jiangshu Du, Can Qin, Ran Xu, Feng Liu, Lichao Sun, Dongwon Lee, Lifu Huang, Wenpeng Yin
conference: "Arxiv"
year: 2025
bibkey: fang2025could
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04279"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Interpretability and Explainability', 'Applications']
---
AI-generated content is becoming increasingly prevalent in the real world,
leading to serious ethical and societal concerns. For instance, adversaries
might exploit large multimodal models (LMMs) to create images that violate
ethical or legal standards, while paper reviewers may misuse large language
models (LLMs) to generate reviews without genuine intellectual effort. While
prior work has explored detecting AI-generated images and texts, and
occasionally tracing their source models, there is a lack of a systematic and
fine-grained comparative study. Important dimensions--such as AI-generated
images vs. text, fully vs. partially AI-generated images, and general vs.
malicious use cases--remain underexplored. Furthermore, whether AI systems like
GPT-4o can explain why certain forged content is attributed to specific
generative models is still an open question, with no existing benchmark
addressing this. To fill this gap, we introduce AI-FAKER, a comprehensive
multimodal dataset with over 280,000 samples spanning multiple LLMs and LMMs,
covering both general and malicious use cases for AI-generated images and
texts. Our experiments reveal two key findings: (i) AI authorship detection
depends not only on the generated output but also on the model's original
training intent; and (ii) GPT-4o provides highly consistent but less specific
explanations when analyzing content produced by OpenAI's own models, such as
DALL-E and GPT-4o itself.
