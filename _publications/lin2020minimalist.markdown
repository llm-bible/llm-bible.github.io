---
layout: publication
title: Mintl Minimalist Transfer Learning For Task45;oriented Dialogue Systems
authors: Lin Zhaojiang, Madotto Andrea, Winata Genta Indra, Fung Pascale
conference: "Arxiv"
year: 2020
bibkey: lin2020minimalist
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.12005"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Tools', 'Training Techniques']
---
In this paper we propose Minimalist Transfer Learning (MinTL) to simplify the system design process of task45;oriented dialogue systems and alleviate the over45;dependency on annotated data. MinTL is a simple yet effective transfer learning framework which allows us to plug45;and45;play pre45;trained seq2seq models and jointly learn dialogue state tracking and dialogue response generation. Unlike previous approaches which use a copy mechanism to carryover the old dialogue states to the new one we introduce Levenshtein belief spans (Lev) that allows efficient dialogue state tracking with a minimal generation length. We instantiate our learning framework with two pre45;trained backbones T5 and BART and evaluate them on MultiWOZ. Extensive experiments demonstrate that 1) our systems establish new state45;of45;the45;art results on end45;to45;end response generation 2) MinTL45;based systems are more robust than baseline methods in the low resource setting and they achieve competitive results with only 2037; training data and 3) Lev greatly improves the inference efficiency.
