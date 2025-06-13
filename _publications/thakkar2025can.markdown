---
layout: publication
title: 'Can LLM Feedback Enhance Review Quality? A Randomized Study Of 20K Reviews At ICLR 2025'
authors: Nitya Thakkar, Mert Yuksekgonul, Jake Silberg, Animesh Garg, Nanyun Peng, Fei Sha, Rose Yu, Carl Vondrick, James Zou
conference: "Arxiv"
year: 2025
bibkey: thakkar2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.09737'}
  - {name: "Code", url: 'https://github.com/zou-group/review_feedback_agent'}
tags: ['Agentic', 'Has Code', 'RAG', 'Tools', 'Survey Paper', 'ICLR']
---
Peer review at AI conferences is stressed by rapidly rising submission
volumes, leading to deteriorating review quality and increased author
dissatisfaction. To address these issues, we developed Review Feedback Agent, a
system leveraging multiple large language models (LLMs) to improve review
clarity and actionability by providing automated feedback on vague comments,
content misunderstandings, and unprofessional remarks to reviewers. Implemented
at ICLR 2025 as a large randomized control study, our system provided optional
feedback to more than 20,000 randomly selected reviews. To ensure high-quality
feedback for reviewers at this scale, we also developed a suite of automated
reliability tests powered by LLMs that acted as guardrails to ensure feedback
quality, with feedback only being sent to reviewers if it passed all the tests.
The results show that 27% of reviewers who received feedback updated their
reviews, and over 12,000 feedback suggestions from the agent were incorporated
by those reviewers. This suggests that many reviewers found the AI-generated
feedback sufficiently helpful to merit updating their reviews. Incorporating AI
feedback led to significantly longer reviews (an average increase of 80 words
among those who updated after receiving feedback) and more informative reviews,
as evaluated by blinded researchers. Moreover, reviewers who were selected to
receive AI feedback were also more engaged during paper rebuttals, as seen in
longer author-reviewer discussions. This work demonstrates that carefully
designed LLM-generated review feedback can enhance peer review quality by
making reviews more specific and actionable while increasing engagement between
reviewers and authors. The Review Feedback Agent is publicly available at
https://github.com/zou-group/review_feedback_agent.
