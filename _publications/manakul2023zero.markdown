---
layout: publication
title: Selfcheckgpt Zero45;resource Black45;box Hallucination Detection For Generative Large Language Models
authors: Potsawee Manakul, Adian Liusie, Mark J. F. Gales
conference: "Arxiv"
year: 2023
bibkey: manakul2023zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2303.08896v3"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
Generative Large Language Models (LLMs) such as GPT45;3 are capable of generating highly fluent responses to a wide variety of user prompts. However LLMs are known to hallucinate facts and make non45;factual statements which can undermine trust in their output. Existing fact45;checking approaches either require access to the output probability distribution (which may not be available for systems such as ChatGPT) or external databases that are interfaced via separate often complex modules. In this work we propose SelfCheckGPT a simple sampling45;based approach that can be used to fact45;check the responses of black45;box models in a zero45;resource fashion i.e. without an external database. SelfCheckGPT leverages the simple idea that if an LLM has knowledge of a given concept sampled responses are likely to be similar and contain consistent facts. However for hallucinated facts stochastically sampled responses are likely to diverge and contradict one another. We investigate this approach by using GPT45;3 to generate passages about individuals from the WikiBio dataset and manually annotate the factuality of the generated passages. We demonstrate that SelfCheckGPT can i) detect non45;factual and factual sentences; and ii) rank passages in terms of factuality. We compare our approach to several baselines and show that our approach has considerably higher AUC45;PR scores in sentence45;level hallucination detection and higher correlation scores in passage45;level factuality assessment compared to grey45;box methods.
