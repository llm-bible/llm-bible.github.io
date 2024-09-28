---
layout: publication
title: MBBQ A Dataset for Cross-Lingual Comparison of Stereotypes in Generative LLMs
authors: Neplenbroek Vera, Bisazza Arianna, Fernández Raquel
conference: "Arxiv"
year: 2024
bibkey: neplenbroek2024mbbq
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07243"}
  - {name: "Code", url: "https://github.com/Veranep/MBBQ"}
tags: ['ARXIV', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'LLM', 'Pretraining Methods', 'RAG', 'Responsible AI']
---
Generative large language models (LLMs) have been shown to exhibit harmful biases and stereotypes. While safety fine-tuning typically takes place in English if at all these models are being used by speakers of many different languages. There is existing evidence that the performance of these models is inconsistent across languages and that they discriminate based on demographic factors of the user. Motivated by this we investigate whether the social stereotypes exhibited by LLMs differ as a function of the language used to prompt them while controlling for cultural differences and task accuracy. To this end we present MBBQ (Multilingual Bias Benchmark for Question-answering) a carefully curated version of the English BBQ dataset extended to Dutch Spanish and Turkish which measures stereotypes commonly held across these languages. We further complement MBBQ with a parallel control dataset to measure task performance on the question-answering task independently of bias. Our results based on several open-source and proprietary LLMs confirm that some non-English languages suffer from bias more than English even when controlling for cultural shifts. Moreover we observe significant cross-lingual differences in bias behaviour for all except the most accurate models. With the release of MBBQ we hope to encourage further research on bias in multilingual settings. The dataset and code are available at https://github.com/Veranep/MBBQ.
