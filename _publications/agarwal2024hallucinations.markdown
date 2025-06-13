---
layout: publication
title: 'Medhalu: Hallucinations In Responses To Healthcare Queries By Large Language Models'
authors: Vibhor Agarwal, Yiqiao Jin, Mohit Chandra, Munmun De Choudhury, Srijan Kumar, Nishanth Sastry
conference: "Arxiv"
year: 2024
bibkey: agarwal2024hallucinations
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19492"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT']
---
The remarkable capabilities of large language models (LLMs) in language
understanding and generation have not rendered them immune to hallucinations.
LLMs can still generate plausible-sounding but factually incorrect or
fabricated information. As LLM-empowered chatbots become popular, laypeople may
frequently ask health-related queries and risk falling victim to these LLM
hallucinations, resulting in various societal and healthcare implications. In
this work, we conduct a pioneering study of hallucinations in LLM-generated
responses to real-world healthcare queries from patients. We propose MedHalu, a
carefully crafted first-of-its-kind medical hallucination dataset with a
diverse range of health-related topics and the corresponding hallucinated
responses from LLMs with labeled hallucination types and hallucinated text
spans. We also introduce MedHaluDetect framework to evaluate capabilities of
various LLMs in detecting hallucinations. We also employ three groups of
evaluators -- medical experts, LLMs, and laypeople -- to study who are more
vulnerable to these medical hallucinations. We find that LLMs are much worse
than the experts. They also perform no better than laypeople and even worse in
few cases in detecting hallucinations. To fill this gap, we propose
expert-in-the-loop approach to improve hallucination detection through LLMs by
infusing expert reasoning. We observe significant performance gains for all the
LLMs with an average macro-F1 improvement of 6.3 percentage points for GPT-4.
