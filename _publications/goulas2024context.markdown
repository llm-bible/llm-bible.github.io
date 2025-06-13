---
layout: publication
title: 'Vidctx: Context-aware Video Question Answering With Image Models'
authors: Andreas Goulas, Vasileios Mezaris, Ioannis Patras
conference: "Arxiv"
year: 2024
bibkey: goulas2024context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.17415'}
  - {name: "Code", url: 'https://github.com/IDT-ITI/VidCtx'}
tags: ['Has Code', 'Training Techniques', 'Applications', 'Tools', 'Prompting', 'Multimodal Models']
---
To address computational and memory limitations of Large Multimodal Models in
the Video Question-Answering task, several recent methods extract textual
representations per frame (e.g., by captioning) and feed them to a Large
Language Model (LLM) that processes them to produce the final response.
However, in this way, the LLM does not have access to visual information and
often has to process repetitive textual descriptions of nearby frames. To
address those shortcomings, in this paper, we introduce VidCtx, a novel
training-free VideoQA framework which integrates both modalities, i.e. both
visual information from input frames and textual descriptions of others frames
that give the appropriate context. More specifically, in the proposed framework
a pre-trained Large Multimodal Model (LMM) is prompted to extract at regular
intervals, question-aware textual descriptions (captions) of video frames.
Those will be used as context when the same LMM will be prompted to answer the
question at hand given as input a) a certain frame, b) the question and c) the
context/caption of an appropriate frame. To avoid redundant information, we
chose as context the descriptions of distant frames. Finally, a simple yet
effective max pooling mechanism is used to aggregate the frame-level decisions.
This methodology enables the model to focus on the relevant segments of the
video and scale to a high number of frames. Experiments show that VidCtx
achieves competitive performance among approaches that rely on open models on
three public Video QA benchmarks, NExT-QA, IntentQA and STAR. Our code is
available at https://github.com/IDT-ITI/VidCtx.
