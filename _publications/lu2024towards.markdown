---
layout: publication
title: Towards Transfer Unlearning Empirical Evidence of Cross-Domain Bias Mitigation
authors: Lu Huimin, Isonuma Masaru, Mori Junichiro, Sakata Ichiro
conference: "Arxiv"
year: 2024
bibkey: lu2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16951"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Language Modeling', 'Training Techniques']
---
Large language models (LLMs) often inherit biases from vast amounts of training corpora. Traditional debiasing methods while effective to some extent do not completely eliminate memorized biases and toxicity in LLMs. In this paper we study an unlearning-based approach to debiasing in LLMs by performing gradient ascent on hate speech against minority groups i.e. minimizing the likelihood of biased or toxic content. Specifically we propose a mask language modeling unlearning technique which unlearns the harmful part of the text. This method enables LLMs to selectively forget and disassociate from biased and harmful content. Experimental results demonstrate the effectiveness of our approach in diminishing bias while maintaining the language modeling abilities. Surprisingly the results also unveil an unexpected potential for cross-domain transfer unlearning debiasing in one bias form (e.g. gender) may contribute to mitigating others (e.g. race and religion).
