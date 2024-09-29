---
layout: publication
title: Cant Remember Details In Long Documents You Need Some Ramp;r
authors: Agrawal Devanshu, Gao Shang, Gajek Martin
conference: "Arxiv"
year: 2024
bibkey: agrawal2024remember
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.05004"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
Long45;context large language models (LLMs) hold promise for tasks such as question45;answering (QA) over long documents but they tend to miss important information in the middle of context documents (arXiv2307.03172v3). Here we introduce textit123;Ramp;R125; 45;45; a combination of two novel prompt45;based methods called textit123;reprompting125; and textit123;in45;context retrieval125; (ICR) 45;45; to alleviate this effect in document45;based QA. In reprompting we repeat the prompt instructions periodically throughout the context document to remind the LLM of its original task. In ICR rather than instructing the LLM to answer the question directly we instruct it to retrieve the top k passage numbers most relevant to the given question which are then used as an abbreviated context in a second QA prompt. We test Ramp;R with GPT45;4 Turbo and Claude45;2.1 on documents up to 80k tokens in length and observe a 1645;point boost in QA accuracy on average. Our further analysis suggests that Ramp;R improves performance on long document45;based QA because it reduces the distance between relevant context and the instructions. Finally we show that compared to short45;context chunkwise methods Ramp;R enables the use of larger chunks that cost fewer LLM calls and output tokens while minimizing the drop in accuracy.
