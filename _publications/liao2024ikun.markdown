---
layout: publication
title: IKUN For WMT24 General MT Task Llms Are Here For Multilingual Machine Translation
authors: Liao Baohao, Herold Christian, Khadivi Shahram, Monz Christof
conference: "Arxiv"
year: 2024
bibkey: liao2024ikun
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11512"}
tags: ['Applications', 'RAG', 'Security', 'Training Techniques']
---
This paper introduces two multilingual systems IKUN and IKUN45;C developed for the general machine translation task in WMT24. IKUN and IKUN45;C represent an open system and a constrained system respectively built on Llama45;345;8b and Mistral45;7B45;v0.3. Both systems are designed to handle all 11 language directions using a single model. According to automatic evaluation metrics IKUN45;C achieved 6 first45;place and 3 second45;place finishes among all constrained systems while IKUN secured 1 first45;place and 2 second45;place finishes across both open and constrained systems. These encouraging results suggest that large language models (LLMs) are nearing the level of proficiency required for effective multilingual machine translation. The systems are based on a two45;stage approach first continuous pre45;training on monolingual data in 10 languages followed by fine45;tuning on high45;quality parallel data for 11 language directions. The primary difference between IKUN and IKUN45;C lies in their monolingual pre45;training strategy. IKUN45;C is pre45;trained using constrained monolingual data whereas IKUN leverages monolingual data from the OSCAR dataset. In the second phase both systems are fine45;tuned on parallel data sourced from NTREX Flores and WMT1645;23 for all 11 language pairs.
