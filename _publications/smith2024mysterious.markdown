---
layout: publication
title: 'The Mysterious Case Of Neuron 1512: Injectable Realignment Architectures Reveal Internal Characteristics Of Meta''s Llama 2 Model'
authors: Brenden Smith, Dallin Baker, Clayton Chase, Myles Barney, Kaden Parker, Makenna Allred, Peter Hu, Alex Evans, Nancy Fulda
conference: "Arxiv"
year: 2024
bibkey: smith2024mysterious
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03621"}
  - {name: "Code", url: "https://github.com/DRAGNLabs/injectable-alignment-model"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Interpretability', 'Transformer', 'Has Code', 'Interpretability and Explainability']
---
Large Language Models (LLMs) have an unrivaled and invaluable ability to
"align" their output to a diverse range of human preferences, by mirroring them
in the text they generate. The internal characteristics of such models,
however, remain largely opaque. This work presents the Injectable Realignment
Model (IRM) as a novel approach to language model interpretability and
explainability. Inspired by earlier work on Neural Programming Interfaces, we
construct and train a small network -- the IRM -- to induce emotion-based
alignments within a 7B parameter LLM architecture. The IRM outputs are injected
via layerwise addition at various points during the LLM's forward pass, thus
modulating its behavior without changing the weights of the original model.
This isolates the alignment behavior from the complex mechanisms of the
transformer model. Analysis of the trained IRM's outputs reveals a curious
pattern. Across more than 24 training runs and multiple alignment datasets,
patterns of IRM activations align themselves in striations associated with a
neuron's index within each transformer layer, rather than being associated with
the layers themselves. Further, a single neuron index (1512) is strongly
correlated with all tested alignments. This result, although initially
counterintuitive, is directly attributable to design choices present within
almost all commercially available transformer architectures, and highlights a
potential weak point in Meta's pretrained Llama 2 models. It also demonstrates
the value of the IRM architecture for language model analysis and
interpretability. Our code and datasets are available at
https://github.com/DRAGNLabs/injectable-alignment-model
