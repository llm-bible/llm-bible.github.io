---
layout: publication
title: 'Extrinsically-focused Evaluation Of Omissions In Medical Summarization'
authors: Elliot Schumacher, Daniel Rosenthal, Dhruv Naik, Varun Nair, Luladay Price, Geoffrey Tso, Anitha Kannan
conference: "Arxiv"
year: 2023
bibkey: schumacher2023extrinsically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08303"}
tags: ['Responsible AI', 'Model Architecture', 'Applications', 'GPT']
---
Large language models (LLMs) have shown promise in safety-critical
applications such as healthcare, yet the ability to quantify performance has
lagged. An example of this challenge is in evaluating a summary of the
patient's medical record. A resulting summary can enable the provider to get a
high-level overview of the patient's health status quickly. Yet, a summary that
omits important facts about the patient's record can produce a misleading
picture. This can lead to negative consequences on medical decision-making. We
propose MED-OMIT as a metric to explore this challenge. We focus on using
provider-patient history conversations to generate a subjective (a summary of
the patient's history) as a case study. We begin by discretizing facts from the
dialogue and identifying which are omitted from the subjective. To determine
which facts are clinically relevant, we measure the importance of each fact to
a simulated differential diagnosis. We compare MED-OMIT's performance to that
of clinical experts and find broad agreement We use MED-OMIT to evaluate LLM
performance on subjective generation and find some LLMs (gpt-4 and
llama-3.1-405b) work well with little effort, while others (e.g. Llama 2)
perform worse.
