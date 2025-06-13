---
layout: publication
title: 'Recurrentgemma: Moving Past Transformers For Efficient Open Language Models'
authors: Aleksandar Botev, Soham De, Samuel L Smith, Anushan Fernando, George-cristian Muraru, Ruba Haroun, Leonard Berrada, Razvan Pascanu, Pier Giuseppe Sessa, Robert Dadashi, Léonard Hussenot, Johan Ferret, Sertan Girgin, Olivier Bachem, Alek Andreev, Kathleen Kenealy, Thomas Mesnard, Cassidy Hardin, Surya Bhupatiraju, Shreya Pathak, Laurent Sifre, Morgane Rivière, Mihir Sanjay Kale, Juliette Love, Pouya Tafti, Armand Joulin, Noah Fiedel, Evan Senter, Yutian Chen, Srivatsan Srinivasan, Guillaume Desjardins, David Budden, Arnaud Doucet, Sharad Vikram, Adam Paszke, Trevor Gale, Sebastian Borgeaud, Charlie Chen, Andy Brock, Antonia Paterson, Jenny Brennan, Meg Risdal, Raj Gundluru, Nesh Devanathan, Paul Mooney, Nilay Chauhan, Phil Culliton, Luiz Gustavo Martins, Elisa Bandy, David Huntsperger, Glenn Cameron, Arthur Zucker, Tris Warkentin, Ludovic Peran, Minh Giang, Zoubin Ghahramani, Clément Farabet, Koray Kavukcuoglu, Demis Hassabis, Raia Hadsell, Yee Whye Teh, Nando De Frietas
conference: "Arxiv"
year: 2024
bibkey: botev2024moving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07839"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
We introduce RecurrentGemma, a family of open language models which uses
Google's novel Griffin architecture. Griffin combines linear recurrences with
local attention to achieve excellent performance on language. It has a
fixed-sized state, which reduces memory use and enables efficient inference on
long sequences. We provide two sizes of models, containing 2B and 9B
parameters, and provide pre-trained and instruction tuned variants for both.
Our models achieve comparable performance to similarly-sized Gemma baselines
despite being trained on fewer tokens.
