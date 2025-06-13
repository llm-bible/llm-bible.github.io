---
layout: publication
title: 'AI2T: Building Trustable AI Tutors By Interactively Teaching A Self-aware Learning Agent'
authors: Daniel Weitekamp, Erik Harpstead, Kenneth Koedinger
conference: "Arxiv"
year: 2024
bibkey: weitekamp2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17924"}
tags: ['Agentic', 'Training Techniques']
---
AI2T is an interactively teachable AI for authoring intelligent tutoring
systems (ITSs). Authors tutor AI2T by providing a few step-by-step solutions
and then grading AI2T's own problem-solving attempts. From just 20-30 minutes
of interactive training, AI2T can induce robust rules for step-by-step solution
tracking (i.e., model-tracing). As AI2T learns it can accurately estimate its
certainty of performing correctly on unseen problem steps using STAND: a
self-aware precondition learning algorithm that outperforms state-of-the-art
methods like XGBoost. Our user study shows that authors can use STAND's
certainty heuristic to estimate when AI2T has been trained on enough diverse
problems to induce correct and complete model-tracing programs. AI2T-induced
programs are more reliable than hallucination-prone LLMs and prior
authoring-by-tutoring approaches. With its self-aware induction of hierarchical
rules, AI2T offers a path toward trustable data-efficient authoring-by-tutoring
for complex ITSs that normally require as many as 200-300 hours of programming
per hour of instruction.
