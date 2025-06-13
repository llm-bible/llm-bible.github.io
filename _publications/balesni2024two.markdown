---
layout: publication
title: 'The Two-hop Curse: Llms Trained On A\(\rightarrow\)b, B\(\rightarrow\)c Fail To Learn A\(\rightarrow\)c'
authors: Mikita Balesni, Tomek Korbak, Owain Evans
conference: "Arxiv"
year: 2024
bibkey: balesni2024two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16353"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
[Notice: This version is outdated. Recent research contradicts some key
claims; we are working on a major revision with more nuanced analysis. Please
wait for the updated version.]
  While LLMs excel at multi-hop questions (e.g. "Who is the spouse of the
performer of Imagine?") when using chain-of-thought reasoning (CoT), they
struggle when forced to reason internally (without CoT). Previous work on the
size and nature of this gap produced mixed evidence with inconclusive results.
In this paper, we introduce a controlled setting for investigating two-hop
reasoning in LLMs, where the above-chance performance constitutes undeniable
evidence for latent reasoning. We fine-tune LLMs (including Llama 3 8B Instruct
and GPT-4o) on fictional facts and confirm that they generalize to answering
two-hop questions about them using CoT. We find that models can perform latent
reasoning when facts appear together during training or in the prompt. However,
to our surprise, models completely fail at two-hop reasoning without CoT when
learned facts only appear in different documents, achieving chance-level
accuracy and chance-level test loss. We call this complete failure to compose
separately learned facts the Two-Hop Curse. Moreover, we evaluate 9 frontier
LLMs on real-world facts, finding that models completely fail at two-hop no-CoT
reasoning for over half of question categories while maintaining partial
success with CoT across most categories. These results suggest that LLMs lack a
general capability for latent multi-hop reasoning independent of the question
type.
