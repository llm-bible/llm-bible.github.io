---
layout: publication
title: 'Large Language Models For In-context Student Modeling: Synthesizing Student''s Behavior In Visual Programming'
authors: Manh Hung Nguyen, Sebastian Tschiatschek, Adish Singla
conference: "Arxiv"
year: 2023
bibkey: nguyen2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10690"}
tags: ['RAG', 'Model Architecture', 'GPT', 'Tools']
---
Student modeling is central to many educational technologies as it enables
predicting future learning outcomes and designing targeted instructional
strategies. However, open-ended learning domains pose challenges for accurately
modeling students due to the diverse behaviors and a large space of possible
misconceptions. To approach these challenges, we explore the application of
large language models (LLMs) for in-context student modeling in open-ended
learning domains. More concretely, given a particular student's attempt on a
reference task as observation, the objective is to synthesize the student's
attempt on a target task. We introduce a novel framework, LLM for Student
Synthesis (LLM-SS), that leverages LLMs for synthesizing a student's behavior.
Our framework can be combined with different LLMs; moreover, we fine-tune LLMs
to boost their student modeling capabilities. We instantiate several methods
based on LLM-SS framework and evaluate them using an existing benchmark,
StudentSyn, for student attempt synthesis in a visual programming domain.
Experimental results show that our methods perform significantly better than
the baseline method NeurSS provided in the StudentSyn benchmark. Furthermore,
our method using a fine-tuned version of the GPT-3.5 model is significantly
better than using the base GPT-3.5 model and gets close to human tutors'
performance.
