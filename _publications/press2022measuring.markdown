---
layout: publication
title: Measuring And Narrowing The Compositionality Gap In Language Models
authors: Ofir Press, Muru Zhang, Sewon Min, Ludwig Schmidt, Noah A. Smith, Mike Lewis
conference: "Arxiv"
year: 2022
bibkey: press2022measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.03350v3"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
We investigate the ability of language models to perform compositional reasoning tasks where the overall solution depends on correctly composing the answers to sub45;problems. We measure how often models can correctly answer all sub45;problems but not generate the overall solution a ratio we call the compositionality gap. We evaluate this ratio by asking multi45;hop questions with answers that require composing multiple facts unlikely to have been observed together during pretraining. In the GPT45;3 family of models as model size increases we show that the single45;hop question answering performance improves faster than the multi45;hop performance does therefore the compositionality gap does not decrease. This surprising result suggests that while more powerful models memorize and recall more factual knowledge they show no corresponding improvement in their ability to perform this kind of compositional reasoning. We then demonstrate how elicitive prompting (such as chain of thought) narrows the compositionality gap by reasoning explicitly. We present a new method self45;ask that further improves on chain of thought. In our method the model explicitly asks itself (and answers) follow45;up questions before answering the initial question. We finally show that self45;asks structured prompting lets us easily plug in a search engine to answer the follow45;up questions which additionally improves accuracy.
