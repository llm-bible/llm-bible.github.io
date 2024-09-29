---
layout: publication
title: Self45;directed Turing Test For Large Language Models
authors: Wu Weiqi, Wu Hongqiu, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: wu2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09853"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods']
---
The Turing test examines whether AIs can exhibit human45;like behaviour in natural language conversations. Traditional Turing tests adopt a rigid dialogue format where each participant sends only one message each time and require continuous human involvement to direct the entire interaction with the test subject. This fails to reflect a natural conversational style and hinders the evaluation of Large Language Models (LLMs) in complex and prolonged dialogues. This paper proposes the Self45;Directed Turing Test which extends the original test with a burst dialogue format allowing more dynamic exchanges by multiple consecutive messages. It further efficiently reduces human workload by having the LLM self45;direct the majority of the test process iteratively generating dialogues that simulate its interaction with humans. With the pseudo45;dialogue history the model then engages in a shorter dialogue with a human which is paired with a human45;human conversation on the same topic to be judged using questionnaires. We introduce the X45;Turn Pass45;Rate metric to assess the human likeness of LLMs across varying durations. While LLMs like GPT45;4 initially perform well achieving pass rates of 51.937; and 38.937; during 3 turns and 10 turns of dialogues respectively their performance drops as the dialogue progresses which underscores the difficulty in maintaining consistency in the long term.
