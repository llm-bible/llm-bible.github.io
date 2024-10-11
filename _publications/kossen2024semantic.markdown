---
layout: publication
title: 'Semantic Entropy Probes: Robust And Cheap Hallucination Detection In Llms'
authors: Kossen Jannik, Han Jiatong, Razzak Muhammed, Schut Lisa, Malik Shreshth, Gal Yarin
conference: "Arxiv"
year: 2024
bibkey: kossen2024semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15927"}
tags: ['Uncategorized']
---
We propose semantic entropy probes (SEPs), a cheap and reliable method for uncertainty quantification in Large Language Models (LLMs). Hallucinations, which are plausible-sounding but factually incorrect and arbitrary model generations, present a major challenge to the practical adoption of LLMs. Recent work by Farquhar et al. (2024) proposes semantic entropy (SE), which can detect hallucinations by estimating uncertainty in the space semantic meaning for a set of model generations. However, the 5-to-10-fold increase in computation cost associated with SE computation hinders practical adoption. To address this, we propose SEPs, which directly approximate SE from the hidden states of a single generation. SEPs are simple to train and do not require sampling multiple model generations at test time, reducing the overhead of semantic uncertainty quantification to almost zero. We show that SEPs retain high performance for hallucination detection and generalize better to out-of-distribution data than previous probing methods that directly predict model accuracy. Our results across models and tasks suggest that model hidden states capture SE, and our ablation studies give further insights into the token positions and model layers for which this is the case.
