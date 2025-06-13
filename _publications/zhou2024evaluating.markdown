---
layout: publication
title: 'Evaluating The Smooth Control Of Attribute Intensity In Text Generation With Llms'
authors: Shang Zhou, Feng Yao, Chengyu Dong, Zihan Wang, Jingbo Shang
conference: "Arxiv"
year: 2024
bibkey: zhou2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04460"}
  - {name: "Code", url: "https://github.com/ShangDataLab/Smooth-Control"}
tags: ['Tools', 'GPT', 'Applications', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Training Techniques', 'Has Code', 'Prompting']
---
Controlling the attribute intensity of text generation is crucial across
scenarios (e.g., writing conciseness, chatting emotion, and explanation
clarity). The remarkable capabilities of large language models (LLMs) have
revolutionized text generation, prompting us to explore such *smooth
control* of LLM generation. Specifically, we propose metrics to assess the
range, calibration, and consistency of the generated text's attribute intensity
in response to varying control values, as well as its relevance to the intended
context. To quantify the attribute intensity and context relevance, we propose
an effective evaluation framework leveraging the Elo rating system and GPT4,
both renowned for their robust alignment with human judgment. We look into two
viable training-free methods for achieving smooth control of LLMs: (1)
Prompting with semantic shifters, and (2) Modifying internal model
representations. The evaluations of these two methods are conducted on \\(5\\)
different attributes with various models. Our code and dataset can be obtained
from \url\{https://github.com/ShangDataLab/Smooth-Control\}.
