---
layout: publication
title: 'Resurrecting Submodularity For Neural Text Generation'
authors: Simeng Han, Xiang Lin, Shafiq Joty
conference: "Arxiv"
year: 2019
bibkey: han2019resurrecting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1911.03014'}
tags: ['Attention Mechanism', 'Language Modeling', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Applications']
---
Submodularity is desirable for a variety of objectives in content selection
where the current neural encoder-decoder framework is inadequate. However, it
has so far not been explored in the neural encoder-decoder system for text
generation. In this work, we define diminishing attentions with submodular
functions and in turn, prove the submodularity of the effective neural
coverage. The greedy algorithm approximating the solution to the submodular
maximization problem is not suited to attention score optimization in
auto-regressive generation. Therefore instead of following how submodular
function has been widely used, we propose a simplified yet principled solution.
The resulting attention module offers an architecturally simple and empirically
effective method to improve the coverage of neural text generation. We run
experiments on three directed text generation tasks with different levels of
recovering rate, across two modalities, three different neural model
architectures and two training strategy variations. The results and analyses
demonstrate that our method generalizes well across these settings, produces
texts of good quality and outperforms state-of-the-art baselines.
