---
layout: publication
title: Semvlp Vision45;language Pre45;training By Aligning Semantics At Multiple Levels
authors: Li Chenliang, Yan Ming, Xu Haiyang, Luo Fuli, Wang Wei, Bi Bin, Huang Songfang
conference: "Arxiv"
year: 2021
bibkey: li2021vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.07829"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Vision45;language pre45;training (VLP) on large45;scale image45;text pairs has recently witnessed rapid progress for learning cross45;modal representations. Existing pre45;training methods either directly concatenate image representation and text representation at a feature level as input to a single45;stream Transformer or use a two45;stream cross45;modal Transformer to align the image45;text representation at a high45;level semantic space. In real45;world image45;text data we observe that it is easy for some of the image45;text pairs to align simple semantics on both modalities while others may be related after higher45;level abstraction. Therefore in this paper we propose a new pre45;training method SemVLP which jointly aligns both the low45;level and high45;level semantics between image and text representations. The model is pre45;trained iteratively with two prevalent fashions single45;stream pre45;training to align at a fine45;grained feature level and two45;stream pre45;training to align high45;level semantics by employing a shared Transformer network with a pluggable cross45;modal attention module. An extensive set of experiments have been conducted on four well45;established vision45;language understanding tasks to demonstrate the effectiveness of the proposed SemVLP in aligning cross45;modal representations towards different semantic granularities.
