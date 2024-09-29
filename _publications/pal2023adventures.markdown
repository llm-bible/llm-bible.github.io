---
layout: publication
title: 'Giraffe: Adventures In Expanding Context Lengths In Llms'
authors: Pal Arka, Karkhanis Deep, Roberts Manley, Dooley Samuel, Sundararajan Arvind, Naidu Siddartha
conference: "Arxiv"
year: 2023
bibkey: pal2023adventures
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10882"}
tags: ['Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Survey Paper', 'Transformer']
---
Modern large language models (LLMs) that rely on attention mechanisms are typically trained with fixed context lengths which enforce upper limits on the length of input sequences that they can handle at evaluation time. To use these models on sequences longer than the train-time context length one might employ techniques from the growing family of context length extrapolation methods -- most of which focus on modifying the system of positional encodings used in the attention mechanism to indicate where tokens or activations are located in the input sequence. We conduct a wide survey of existing methods of context length extrapolation on a base LLaMA or LLaMA 2 model and introduce some of our own design as well -- in particular a new truncation strategy for modifying the basis for the position encoding. We test these methods using three new evaluation tasks (FreeFormQA AlteredNumericQA and LongChat-Lines) as well as perplexity which we find to be less fine-grained as a measure of long context performance of LLMs. We release the three tasks publicly as datasets on HuggingFace. We discover that linear scaling is the best method for extending context length and show that further gains can be achieved by using longer scales at evaluation time. We also discover promising extrapolation capabilities in the truncated basis. To support further research in this area we release three new 13B parameter long-context models which we call Giraffe 4k and 16k context models trained from base LLaMA-13B and a 32k context model trained from base LLaMA2-13B. We also release the code to replicate our results.
