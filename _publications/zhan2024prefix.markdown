---
layout: publication
title: Prefix Text As A Yarn Eliciting Non45;english Alignment In Foundation Language Model
authors: Zhan Runzhe, Yang Xinyi, Wong Derek F., Chao Lidia S., Zhang Yue
conference: "Arxiv"
year: 2024
bibkey: zhan2024prefix
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16766"}
tags: ['Applications', 'Fine Tuning', 'Training Techniques']
---
While supervised fine45;tuning (SFT) has been a straightforward approach for tailoring the output of foundation large language model (LLM) to specific preferences concerns have been raised about the depth of this alignment with some critiques suggesting it is merely superficial. We critically examine this hypothesis within the scope of cross45;lingual generation tasks proposing that the effectiveness of SFT may be constrained by its reliance on prior tokens to guide cross45;lingual generation. Based on this crucial insight and in response to the challenges posed by the costly and limited availability of non45;English data for SFT we introduce a novel training45;free alignment method named PreTTY which employs minimal task45;related prior tokens to bridge the foundation LLM and the SFT LLM achieving comparable performance without training. Experiments on machine translation and part45;of45;speech tagging across eight languages demonstrate the efficacy of PreTTY in cross45;lingual settings. Remarkably by initiating the decoding process with only one or two prior tokens foundation LLMs can achieve performance comparable to their SFT counterparts. This method presents a cost45;effective alternative to SFT and advances the democratization of multilingual LLMs.
