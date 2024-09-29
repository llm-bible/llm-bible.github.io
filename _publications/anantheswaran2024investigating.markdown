---
layout: publication
title: Investigating The Robustness Of Llms On Math Word Problems
authors: Anantheswaran Ujjwala, Gupta Himanshu, Scaria Kevin, Verma Shreyas, Baral Chitta, Mishra Swaroop
conference: "Arxiv"
year: 2024
bibkey: anantheswaran2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15444"}
tags: ['Ethics And Bias', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) excel at various tasks including solving math word problems (MWPs) but struggle with real45;world problems containing irrelevant information. To address this we propose a prompting framework that generates adversarial variants of MWPs by adding irrelevant variables. We introduce a dataset ProbleMATHIC containing both adversarial and non45;adversarial MWPs. Our experiments reveal that LLMs are susceptible to distraction by numerical noise resulting in an average relative performance drop of ~2637; on adversarial MWPs. To mitigate this we fine45;tune LLMs (Llama45;2 Mistral) on the adversarial samples from our dataset. Fine45;tuning on adversarial training instances improves performance on adversarial MWPs by ~837; indicating increased robustness to noise and better ability to identify relevant data for reasoning. Finally to assess the generalizability of our prompting framework we introduce GSM45;8K45;Adv an adversarial variant of the GSM45;8K benchmark. LLMs continue to struggle when faced with adversarial information reducing performance by up to ~637;.
