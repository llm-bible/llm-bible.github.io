---
layout: publication
title: 'Exploring Knowledge Tracing In Tutor-student Dialogues Using Llms'
authors: Alexander Scarlatos, Ryan S. Baker, Andrew Lan
conference: "Arxiv"
year: 2024
bibkey: scarlatos2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.16490"}
tags: ['Prompting', 'Reinforcement Learning']
---
Recent advances in large language models (LLMs) have led to the development
of artificial intelligence (AI)-powered tutoring chatbots, showing promise in
providing broad access to high-quality personalized education. Existing works
have studied how to make LLMs follow tutoring principles, but have not studied
broader uses of LLMs for supporting tutoring. Up until now, tracing student
knowledge and analyzing misconceptions has been difficult and time-consuming to
implement for open-ended dialogue tutoring. In this work, we investigate
whether LLMs can be supportive of this task: we first use LLM prompting methods
to identify the knowledge components/skills involved in each dialogue turn,
i.e., a tutor utterance posing a task or a student utterance that responds to
it. We also evaluate whether the student responds correctly to the tutor and
verify the LLM's accuracy using human expert annotations. We then apply a range
of knowledge tracing (KT) methods on the resulting labeled data to track
student knowledge levels over an entire dialogue. We conduct experiments on two
tutoring dialogue datasets, and show that a novel yet simple LLM-based method,
LLMKT, significantly outperforms existing KT methods in predicting student
response correctness in dialogues. We perform extensive qualitative analyses to
highlight the challenges in dialogueKT and outline multiple avenues for future
work.
