---
layout: publication
title: The Unreasonable Ineffectiveness Of Nucleus Sampling On Mitigating Text Memorization
authors: Borec Luka, Sadler Philipp, Schlangen David
conference: "Arxiv"
year: 2024
bibkey: borec2024unreasonable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16345"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Training Techniques']
---
This work analyses the text memorization behavior of large language models (LLMs) when subjected to nucleus sampling. Stochastic decoding methods like nucleus sampling are typically applied to overcome issues such as monotonous and repetitive text generation which are often observed with maximization45;based decoding techniques. We hypothesize that nucleus sampling might also reduce the occurrence of memorization patterns because it could lead to the selection of tokens outside the memorized sequence. To test this hypothesis we create a diagnostic dataset with a known distribution of duplicates that gives us some control over the likelihood of memorization of certain parts of the training data. Our analysis of two GPT45;Neo models fine45;tuned on this dataset interestingly shows that (i) an increase of the nucleus size reduces memorization only modestly and (ii) even when models do not engage in hard memorization 45;45; a verbatim reproduction of training samples 45;45; they may still display soft memorization whereby they generate outputs that echo the training data but without a complete one45;by45;one resemblance.
