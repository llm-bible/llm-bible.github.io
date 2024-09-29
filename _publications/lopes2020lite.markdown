---
layout: publication
title: 'Lite Training Strategies For Portuguese-english And English-portuguese Translation'
authors: Lopes Alexandre, Nogueira Rodrigo, Lotufo Roberto, Pedrini Helio
conference: "Arxiv"
year: 2020
bibkey: lopes2020lite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.08769"}
  - {name: "Code", url: "https://github.com/unicamp-dl/Lite-T5-Translation"}
tags: ['Applications', 'Has Code', 'Tools', 'Training Techniques']
---
Despite the widespread adoption of deep learning for machine translation it is still expensive to develop high-quality translation models. In this work we investigate the use of pre-trained models such as T5 for Portuguese-English and English-Portuguese translation tasks using low-cost hardware. We explore the use of Portuguese and English pre-trained language models and propose an adaptation of the English tokenizer to represent Portuguese characters such as diaeresis acute and grave accents. We compare our models to the Google Translate API and MarianMT on a subset of the ParaCrawl dataset as well as to the winning submission to the WMT19 Biomedical Translation Shared Task. We also describe our submission to the WMT20 Biomedical Translation Shared Task. Our results show that our models have a competitive performance to state-of-the-art models while being trained on modest hardware (a single 8GB gaming GPU for nine days). Our data models and code are available at https://github.com/unicamp-dl/Lite-T5-Translation."
