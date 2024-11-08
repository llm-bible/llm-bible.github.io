---
layout: publication
title: 'Self-directed Turing Test For Large Language Models'
authors: Wu Weiqi, Wu Hongqiu, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: wu2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09853"}
tags: ['GPT', 'Model Architecture']
---
The Turing test examines whether AIs can exhibit human-like behaviour in
natural language conversations. Traditional Turing tests adopt a rigid dialogue
format where each participant sends only one message each time and require
continuous human involvement to direct the entire interaction with the test
subject. This fails to reflect a natural conversational style and hinders the
evaluation of Large Language Models (LLMs) in complex and prolonged dialogues.
This paper proposes the Self-Directed Turing Test, which extends the original
test with a burst dialogue format, allowing more dynamic exchanges by multiple
consecutive messages. It further efficiently reduces human workload by having
the LLM self-direct the majority of the test process, iteratively generating
dialogues that simulate its interaction with humans. With the pseudo-dialogue
history, the model then engages in a shorter dialogue with a human, which is
paired with a human-human conversation on the same topic to be judged using
questionnaires. We introduce the X-Turn Pass-Rate metric to assess the human
likeness of LLMs across varying durations. While LLMs like GPT-4 initially
perform well, achieving pass rates of 51.9% and 38.9% during 3 turns and 10
turns of dialogues respectively, their performance drops as the dialogue
progresses, which underscores the difficulty in maintaining consistency in the
long term.
