---
layout: publication
title: 'Contrastive Perplexity For Controlled Generation: An Application In Detoxifying Large Language Models'
authors: Tassilo Klein, Moin Nabi
conference: "Arxiv"
year: 2024
bibkey: klein2024contrastive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.08491'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Pretraining Methods']
---
The generation of toxic content by large language models (LLMs) remains a critical challenge for the safe deployment of language technology. We propose a novel framework for implicit knowledge editing and controlled text generation by fine-tuning LLMs with a prototype-based contrastive perplexity objective. Central to our method is the construction of hard negatives - toxic outputs that are generated through adversarial paraphrasing to be semantically similar and model probability to their non-toxic counterparts. By training on these challenging and realistic pairs, our approach ensures robust and stable contrastive optimization. Experimental results in the domain of detoxification demonstrate that our method significantly reduces toxic generation while maintaining strong performance on downstream tasks such as commonsense reasoning and reading comprehension. Our findings highlight the effectiveness of exploiting hard negatives for attribute-aware fine-tuning.
