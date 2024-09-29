---
layout: publication
title: Peek Across Improving Multi45;document Modeling Via Cross45;document Question45;answering
authors: Caciularu Avi, Peters Matthew E., Goldberger Jacob, Dagan Ido, Cohan Arman
conference: "Arxiv"
year: 2023
bibkey: caciularu2023peek
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15387"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG', 'Training Techniques']
---
The integration of multi45;document pre45;training objectives into language models has resulted in remarkable improvements in multi45;document downstream tasks. In this work we propose extending this idea by pre45;training a generic multi45;document model from a novel cross45;document question answering pre45;training objective. To that end given a set (or cluster) of topically45;related documents we systematically generate semantically45;oriented questions from a salient sentence in one document and challenge the model during pre45;training to answer these questions while peeking into other topically45;related documents. In a similar manner the model is also challenged to recover the sentence from which the question was generated again while leveraging cross45;document information. This novel multi45;document QA formulation directs the model to better recover cross45;text informational relations and introduces a natural augmentation that artificially increases the pre45;training data. Further unlike prior multi45;document models that focus on either classification or summarization tasks our pre45;training objective formulation enables the model to perform tasks that involve both short text generation (e.g. QA) and long text generation (e.g. summarization). Following this scheme we pre45;train our model 45;45; termed QAmden 45;45; and evaluate its performance across several multi45;document tasks including multi45;document QA summarization and query45;focused summarization yielding improvements of up to 737; and significantly outperforms zero45;shot GPT45;3.5 and GPT45;4.
