---
layout: publication
title: 'Got Compute, But No Data: Lessons From Post-training A Finnish LLM'
authors: Elaine Zosa, Ville Komulainen, Sampo Pyysalo
conference: "Proceedings of the Joint 25th Nordic Conference on Computational Linguistics and 11th Baltic Conference on Human Language Technologies (NoDaLiDa/Baltic-HLT 2025)"
year: 2025
bibkey: zosa2025got
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.09407"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning']
---
As LLMs gain more popularity as chatbots and general assistants, methods have
been developed to enable LLMs to follow instructions and align with human
preferences. These methods have found success in the field, but their
effectiveness has not been demonstrated outside of high-resource languages. In
this work, we discuss our experiences in post-training an LLM for
instruction-following for English and Finnish. We use a multilingual LLM to
translate instruction and preference datasets from English to Finnish. We
perform instruction tuning and preference optimization in English and Finnish
and evaluate the instruction-following capabilities of the model in both
languages. Our results show that with a few hundred Finnish instruction samples
we can obtain competitive performance in Finnish instruction-following. We also
found that although preference optimization in English offers some
cross-lingual benefits, we obtain our best results by using preference data
from both languages. We release our model, datasets, and recipes under open
licenses at https://huggingface.co/LumiOpen/Poro-34B-chat-OpenAssistant
