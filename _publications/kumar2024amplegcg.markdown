---
layout: publication
title: 'Amplegcg-plus: A Strong Generative Model Of Adversarial Suffixes To Jailbreak Llms With Higher Success Rates In Fewer Attempts'
authors: Vishal Kumar, Zeyi Liao, Jaylen Jones, Huan Sun
conference: "Arxiv"
year: 2024
bibkey: kumar2024amplegcg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22143"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Security', 'Training Techniques', 'Attention Mechanism', 'Prompting']
---
Although large language models (LLMs) are typically aligned, they remain
vulnerable to jailbreaking through either carefully crafted prompts in natural
language or, interestingly, gibberish adversarial suffixes. However, gibberish
tokens have received relatively less attention despite their success in
attacking aligned LLMs. Recent work, AmpleGCG~\citep\{liao2024amplegcg\},
demonstrates that a generative model can quickly produce numerous customizable
gibberish adversarial suffixes for any harmful query, exposing a range of
alignment gaps in out-of-distribution (OOD) language spaces. To bring more
attention to this area, we introduce AmpleGCG-Plus, an enhanced version that
achieves better performance in fewer attempts. Through a series of exploratory
experiments, we identify several training strategies to improve the learning of
gibberish suffixes. Our results, verified under a strict evaluation setting,
show that it outperforms AmpleGCG on both open-weight and closed-source models,
achieving increases in attack success rate (ASR) of up to 17% in the white-box
setting against Llama-2-7B-chat, and more than tripling ASR in the black-box
setting against GPT-4. Notably, AmpleGCG-Plus jailbreaks the newer GPT-4o
series of models at similar rates to GPT-4, and, uncovers vulnerabilities
against the recently proposed circuit breakers defense. We publicly release
AmpleGCG-Plus along with our collected training datasets.
