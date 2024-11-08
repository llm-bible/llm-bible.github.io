---
layout: publication
title: 'LACIE: Listener-aware Finetuning For Confidence Calibration In Large Language Models'
authors: Stengel-eskin Elias, Hase Peter, Bansal Mohit
conference: "Arxiv"
year: 2024
bibkey: stengeleskin2024listener
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.21028"}
tags: ['Agentic', 'Efficiency And Optimization', 'RAG', 'Training Techniques']
---
When answering questions, LLMs can convey not only an answer, but a level of
confidence about the answer being correct. This includes explicit confidence
markers (e.g. giving a numeric score) as well as implicit markers, like an
authoritative tone or elaborating with additional knowledge. For LLMs to be
trustworthy knowledge sources, the confidence they convey should match their
actual expertise; however, most current models tend towards overconfidence. To
calibrate both implicit and explicit confidence markers, we introduce a
pragmatic, listener-aware finetuning method (LACIE) that models the listener,
considering not only whether an answer is right, but whether it will be
accepted by a listener. We cast calibration as preference optimization,
creating data via a two-agent game, where a speaker model's outputs are judged
by a simulated listener. We then finetune three LLMs (Mistral-7B, Llama3-8B,
Llama3-70B) with LACIE, and show that the resulting models are better
calibrated w.r.t. a simulated listener. Crucially, these trends transfer to
human listeners, helping them correctly predict model correctness: we conduct a
human evaluation where annotators accept or reject an LLM's answers, finding
that training with LACIE results in 47% fewer incorrect answers being accepted
while maintaining the same level of acceptance for correct answers.
Furthermore, LACIE generalizes to another dataset, resulting in a large
increase in truthfulness on TruthfulQA when trained on TriviaQA. Our analysis
indicates that LACIE leads to a better confidence separation between correct
and incorrect examples. Qualitatively, we find that a LACIE-trained model
hedges more and implicitly signals certainty when it is correct by using an
authoritative tone or including details. Finally, LACIE finetuning leads to an
emergent increase in model abstention (e.g. saying "I don't know") for answers
that are likely wrong.
