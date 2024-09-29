---
layout: publication
title: The Mysterious Case Of Neuron 1512 Injectable Realignment Architectures Reveal Internal Characteristics Of Metas Llama 2 Model
authors: Smith Brenden, Baker Dallin, Chase Clayton, Barney Myles, Parker Kaden, Allred Makenna, Hu Peter, Evans Alex, Fulda Nancy
conference: "Arxiv"
year: 2024
bibkey: smith2024mysterious
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03621"}
  - {name: "Code", url: "https://github.com/DRAGNLabs/injectable-alignment-model"}
tags: ['Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs) have an unrivaled and invaluable ability to align their output to a diverse range of human preferences by mirroring them in the text they generate. The internal characteristics of such models however remain largely opaque. This work presents the Injectable Realignment Model (IRM) as a novel approach to language model interpretability and explainability. Inspired by earlier work on Neural Programming Interfaces we construct and train a small network -- the IRM -- to induce emotion-based alignments within a 7B parameter LLM architecture. The IRM outputs are injected via layerwise addition at various points during the LLMs forward pass thus modulating its behavior without changing the weights of the original model. This isolates the alignment behavior from the complex mechanisms of the transformer model. Analysis of the trained IRMs outputs reveals a curious pattern. Across more than 24 training runs and multiple alignment datasets patterns of IRM activations align themselves in striations associated with a neurons index within each transformer layer rather than being associated with the layers themselves. Further a single neuron index (1512) is strongly correlated with all tested alignments. This result although initially counterintuitive is directly attributable to design choices present within almost all commercially available transformer architectures and highlights a potential weak point in Metas pretrained Llama 2 models. It also demonstrates the value of the IRM architecture for language model analysis and interpretability. Our code and datasets are available at https://github.com/DRAGNLabs/injectable-alignment-model
