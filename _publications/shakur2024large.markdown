---
layout: publication
title: 'Large Language Models For Medical OSCE Assessment: A Novel Approach To Transcript Analysis'
authors: Ameer Hamza Shakur, Michael J. Holcomb, David Hein, Shinyoung Kang, Thomas O. Dalton, Krystle K. Campbell, Daniel J. Scott, Andrew R. Jamieson
conference: "Arxiv"
year: 2024
bibkey: shakur2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12858"}
tags: ['GPT', 'Prompting', 'Applications', 'Model Architecture']
---
Grading Objective Structured Clinical Examinations (OSCEs) is a
time-consuming and expensive process, traditionally requiring extensive manual
effort from human experts. In this study, we explore the potential of Large
Language Models (LLMs) to assess skills related to medical student
communication. We analyzed 2,027 video-recorded OSCE examinations from the
University of Texas Southwestern Medical Center (UTSW), spanning four years
(2019-2022), and several different medical cases or "stations." Specifically,
our focus was on evaluating students' ability to summarize patients' medical
history: we targeted the rubric item 'did the student summarize the patients'
medical history?' from the communication skills rubric. After transcribing
speech audio captured by OSCE videos using Whisper-v3, we studied the
performance of various LLM-based approaches for grading students on this
summarization task based on their examination transcripts. Using various
frontier-level open-source and proprietary LLMs, we evaluated different
techniques such as zero-shot chain-of-thought prompting, retrieval augmented
generation, and multi-model ensemble methods. Our results show that frontier
LLM models like GPT-4 achieved remarkable alignment with human graders,
demonstrating a Cohen's kappa agreement of 0.88 and indicating strong potential
for LLM-based OSCE grading to augment the current grading process. Open-source
models also showed promising results, suggesting potential for widespread,
cost-effective deployment. Further, we present a failure analysis identifying
conditions where LLM grading may be less reliable in this context and recommend
best practices for deploying LLMs in medical education settings.
