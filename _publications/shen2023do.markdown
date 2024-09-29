---
layout: publication
title: Do Pretrained Transformers Learn In-context By Gradient Descent
authors: Shen Lingfeng, Mishra Aayush, Khashabi Daniel
conference: "Arxiv"
year: 2023
bibkey: shen2023do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08540"}
tags: ['In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
The emergence of In-Context Learning (ICL) in LLMs remains a remarkable phenomenon that is partially understood. To explain ICL recent studies have created theoretical connections to Gradient Descent (GD). We ask do such connections hold up in actual pre-trained language models We highlight the limiting assumptions in prior works that make their setup considerably different from the practical setup in which language models are trained. For example their experimental verification uses (emph)ICL objective (training models explicitly for ICL) which differs from the emergent ICL in the wild. Furthermore the theoretical hand-constructed weights used in these studies have properties that dont match those of real LLMs. We also look for evidence in real models. We observe that ICL and GD have different sensitivity to the order in which they observe demonstrations. Finally we probe and compare the ICL vs. GD hypothesis in a natural setting. We conduct comprehensive empirical analyses on language models pre-trained on natural data (LLaMa-7B). Our comparisons of three performance metrics highlight the inconsistent behavior of ICL and GD as a function of various factors such as datasets models and the number of demonstrations. We observe that ICL and GD modify the output distribution of language models differently. These results indicate that (emph)the equivalence between ICL and GD remains an open hypothesis and calls for further studies.
