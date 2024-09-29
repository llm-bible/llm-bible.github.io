---
layout: publication
title: KIWI&#58; A Dataset Of Knowledge-intensive Writing Instructions For Answering Research Questions
authors: Xu Fangyuan, Lo Kyle, Soldaini Luca, Kuehl Bailey, Choi Eunsol, Wadden David
conference: "Arxiv"
year: 2024
bibkey: xu2024dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03866"}
tags: ['Agentic', 'Pretraining Methods']
---
Large language models (LLMs) adapted to follow user instructions are now widely deployed as conversational agents. In this work we examine one increasingly common instruction-following task providing writing assistance to compose a long-form answer. To evaluate the capabilities of current LLMs on this task we construct KIWI a dataset of knowledge-intensive writing instructions in the scientific domain. Given a research question an initial model-generated answer and a set of relevant papers an expert annotator iteratively issues instructions for the model to revise and improve its answer. We collect 1260 interaction turns from 234 interaction sessions with three state-of-the-art LLMs. Each turn includes a user instruction a model response and a human evaluation of the model response. Through a detailed analysis of the collected responses we find that all models struggle to incorporate new information into an existing answer and to perform precise and unambiguous edits. Further we find that models struggle to judge whether their outputs successfully followed user instructions with accuracy at least 10 points short of human agreement. Our findings indicate that KIWI will be a valuable resource to measure progress and improve LLMs instruction-following capabilities for knowledge intensive writing tasks.
