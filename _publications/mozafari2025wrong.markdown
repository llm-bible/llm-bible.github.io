---
layout: publication
title: 'Wrong Answers Can Also Be Useful: Plausibleqa -- A Large-scale QA Dataset With Answer Plausibility Scores'
authors: Jamshid Mozafari, Abdelrahman Abdallah, Bhawna Piryani, Adam Jatowt
conference: "Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025)"
year: 2025
bibkey: mozafari2025wrong
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16358'}
tags: ['Reinforcement Learning', 'Security', 'Applications']
---
Large Language Models (LLMs) are revolutionizing information retrieval, with
chatbots becoming an important source for answering user queries. As by their
design, LLMs prioritize generating correct answers, the value of highly
plausible yet incorrect answers (candidate answers) tends to be overlooked.
However, such answers can still prove useful, for example, they can play a
crucial role in tasks like Multiple-Choice Question Answering (MCQA) and QA
Robustness Assessment (QARA). Existing QA datasets primarily focus on correct
answers without explicit consideration of the plausibility of other candidate
answers, limiting opportunity for more nuanced evaluations of models. To
address this gap, we introduce PlausibleQA, a large-scale dataset comprising
10,000 questions and 100,000 candidate answers, each annotated with
plausibility scores and justifications for their selection. Additionally, the
dataset includes 900,000 justifications for pairwise comparisons between
candidate answers, further refining plausibility assessments. We evaluate
PlausibleQA through human assessments and empirical experiments, demonstrating
its utility in MCQA and QARA analysis. Our findings show that
plausibility-aware approaches are effective for MCQA distractor generation and
QARA. We release PlausibleQA as a resource for advancing QA research and
enhancing LLM performance in distinguishing plausible distractors from correct
answers.
