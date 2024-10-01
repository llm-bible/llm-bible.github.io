---
layout: publication
title: 'Rejection Improves Reliability: Training Llms To Refuse Unknown Questions Using RL From Knowledge Feedback'
authors: Xu Hongshen, Zhu Zichen, Zhang Situo, Ma Da, Fan Shuai, Chen Lu, Yu Kai
conference: "Arxiv"
year: 2024
bibkey: xu2024rejection
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18349"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) often generate erroneous outputs, known as hallucinations, due to their limitations in discerning questions beyond their knowledge scope. While addressing hallucination has been a focal point in research, previous efforts primarily concentrate on enhancing correctness without giving due consideration to the significance of rejection mechanisms. In this paper, we conduct a comprehensive examination of the role of rejection, introducing the notion of model reliability along with corresponding metrics. These metrics measure the model's ability to provide accurate responses while adeptly rejecting questions exceeding its knowledge boundaries, thereby minimizing hallucinations. To improve the inherent reliability of LLMs, we present a novel alignment framework called Reinforcement Learning from Knowledge Feedback (RLKF). RLKF leverages knowledge feedback to dynamically determine the model's knowledge boundary and trains a reliable reward model to encourage the refusal of out-of-knowledge questions. Experimental results on mathematical questions affirm the substantial efficacy of RLKF in significantly enhancing LLM reliability.
