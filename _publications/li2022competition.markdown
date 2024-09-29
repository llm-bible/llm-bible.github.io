---
layout: publication
title: Competition45;level Code Generation With Alphacode
authors: Yujia Li, David Choi, Junyoung Chung, Nate Kushman, Julian Schrittwieser, Rémi Leblond, Tom Eccles, James Keeling, Felix Gimeno, Agustin Dal Lago, Thomas Hubert, Peter Choy, Cyprien De Masson D'autume, Igor Babuschkin, Xinyun Chen, Po-sen Huang, Johannes Welbl, Sven Gowal, Alexey Cherepanov, James Molloy, Daniel J. Mankowitz, Esme Sutherland Robson, Pushmeet Kohli, Nando De Freitas, Koray Kavukcuoglu, Oriol Vinyals
conference: "Arxiv"
year: 2022
bibkey: li2022competition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2203.07814v1"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Programming is a powerful and ubiquitous problem45;solving tool. Developing systems that can assist programmers or even generate programs independently could make programming more productive and accessible yet so far incorporating innovations in AI has proven challenging. Recent large45;scale language models have demonstrated an impressive ability to generate code and are now able to complete simple programming tasks. However these models still perform poorly when evaluated on more complex unseen problems that require problem45;solving skills beyond simply translating instructions into code. For example competitive programming problems which require an understanding of algorithms and complex natural language remain extremely challenging. To address this gap we introduce AlphaCode a system for code generation that can create novel solutions to these problems that require deeper reasoning. In simulated evaluations on recent programming competitions on the Codeforces platform AlphaCode achieved on average a ranking of top 54.337; in competitions with more than 5000 participants. We found that three key components were critical to achieve good and reliable performance (1) an extensive and clean competitive programming dataset for training and evaluation (2) large and efficient45;to45;sample transformer45;based architectures and (3) large45;scale model sampling to explore the search space followed by filtering based on program behavior to a small set of submissions.
