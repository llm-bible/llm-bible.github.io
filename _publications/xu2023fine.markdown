---
layout: publication
title: Fine45;tuned Llms Know More Hallucinate Less With Few45;shot Sequence45;to45;sequence Semantic Parsing Over Wikidata
authors: Xu Silei, Liu Shicheng, Culhane Theo, Pertseva Elizaveta, Wu Meng-hsi, Semnani Sina J., Lam Monica S.
conference: "Arxiv"
year: 2023
bibkey: xu2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14202"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
While large language models (LLMs) can answer many questions correctly they can also hallucinate and give wrong answers. Wikidata with its over 12 billion facts can be used to ground LLMs to improve their factuality. This paper presents WikiWebQuestions a high45;quality question answering benchmark for Wikidata. Ported over from WebQuestions for Freebase it consists of real45;world data with SPARQL annotation. This paper presents a few45;shot sequence45;to45;sequence semantic parser for Wikidata. We modify SPARQL to use the unique domain and property names instead of their IDs. We train the parser to use either the results from an entity linker or mentions in the query. We fine45;tune LLaMA by adding the few45;shot training data to that used to fine45;tune Alpaca. Our experimental results demonstrate the effectiveness of this methodology establishing a strong baseline of 7637; and 6537; answer accuracy in the dev and test sets of WikiWebQuestions respectively. By pairing our semantic parser with GPT45;3 we combine verifiable results with qualified GPT45;3 guesses to provide useful answers to 9637; of the questions in dev. We also show that our method outperforms the state45;of45;the45;art for the QALD45;7 Wikidata dataset by 3.637; in F1 score.
