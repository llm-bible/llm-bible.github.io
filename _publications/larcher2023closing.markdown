---
layout: publication
title: Cabrita Closing The Gap For Foreign Languages
authors: Larcher Celio, Piau Marcos, Finardi Paulo, Gengo Pedro, Esposito Piero, Caridá Vinicius
conference: "Arxiv"
year: 2023
bibkey: larcher2023closing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11878"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Tokenization', 'Training Techniques', 'Transformer']
---
The strategy of training the model from scratch in a specific language or domain serves two essential purposes i) enhancing performance in the particular linguistic or domain context and ii) ensuring effective tokenization. The main limitation inherent to this approach lies in the associated cost which can reach six to seven45;digit dollar values depending on the model size and the number of parameters involved. The main solution to overcome the cost challenge is to rely on available pre45;trained models which despite recent advancements such as the LLaMA and LLaMA45;2 models still demonstrate inefficiency for certain specific domain problems or prove ineffective in scenarios involving conversational memory resources given the large number of tokens required to represent text. To overcome this issue we present a methodology named Cabrita which as our research demonstrates successfully addresses the performance and efficient tokenization problem all at an affordable cost. We believe that this methodology can be applied to any transformer45;like architecture model. To validate the study we conducted continuous pre45;training exclusively using Portuguese text on a 345;billion45;parameter model known as OpenLLaMA resulting in a model named openCabrita 3B. The openCabrita 3B also features a new tokenizer that results in a significant reduction in the number of tokens required to represent the text. In our assessment for few45;shot learning tasks we achieved similar results with this 3B model compared to a traditional continuous pre45;training approach as well as to 7B models English pre45;trained models.
