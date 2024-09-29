---
layout: publication
title: A Simple Meta-learning Paradigm for Zero-shot Intent Classification with Mixture Attention Mechanism
authors: Liu Han, Zhao Siyang, Zhang Xiaotong, Zhang Feng, Sun Junjie, Yu Hong, Zhang Xianchao
conference: "Arxiv"
year: 2022
bibkey: liu2022simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.02179"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Zero-shot intent classification is a vital and challenging task in dialogue systems which aims to deal with numerous fast-emerging unacquainted intents without annotated training data. To obtain more satisfactory performance the crucial points lie in two aspects extracting better utterance features and strengthening the model generalization ability. In this paper we propose a simple yet effective meta-learning paradigm for zero-shot intent classification. To learn better semantic representations for utterances we introduce a new mixture attention mechanism which encodes the pertinent word occurrence patterns by leveraging the distributional signature attention and multi-layer perceptron attention simultaneously. To strengthen the transfer ability of the model from seen classes to unseen classes we reformulate zero-shot intent classification with a meta-learning strategy which trains the model by simulating multiple zero-shot classification tasks on seen categories and promotes the model generalization ability with a meta-adapting procedure on mimic unseen categories. Extensive experiments on two real-world dialogue datasets in different languages show that our model outperforms other strong baselines on both standard and generalized zero-shot intent classification tasks.
