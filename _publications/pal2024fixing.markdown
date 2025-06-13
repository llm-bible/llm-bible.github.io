---
layout: publication
title: 'Smaug: Fixing Failure Modes Of Preference Optimisation With Dpo-positive'
authors: Arka Pal, Deep Karkhanis, Samuel Dooley, Manley Roberts, Siddartha Naidu, Colin White
conference: "Arxiv"
year: 2024
bibkey: pal2024fixing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13228"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Direct Preference Optimisation (DPO) is effective at significantly improving
the performance of large language models (LLMs) on downstream tasks such as
reasoning, summarisation, and alignment. Using pairs of preferred and
dispreferred data, DPO models the relative probability of picking one response
over another. In this work, first we show theoretically that the standard DPO
loss can lead to a reduction of the model's likelihood of the preferred
examples, as long as the relative probability between the preferred and
dispreferred classes increases. We then show empirically that this phenomenon
occurs when fine-tuning LLMs on common datasets, especially datasets in which
the edit distance between pairs of completions is low. Using these insights, we
design DPO-Positive (DPOP), a new loss function and training procedure which
avoids this failure mode. Surprisingly, we find that DPOP outperforms DPO and
other fine-tuning procedures across a wide variety of datasets and downstream
tasks, including datasets with high edit distances between completions.
Furthermore, we find that the DPOP-tuned model outperforms the DPO-tuned model
(all else equal) on benchmarks independent of the fine-tuning data, such as
MT-Bench. Finally, using DPOP, we create and open-source Smaug-34B and
Smaug-72B, with the latter becoming the first open-source LLM to surpass an
average accuracy of 80% on the HuggingFace Open LLM Leaderboard.
