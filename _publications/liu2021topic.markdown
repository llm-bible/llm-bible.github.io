---
layout: publication
title: Topic-aware Contrastive Learning For Abstractive Dialogue Summarization
authors: Junpeng Liu et al.
conference: Arxiv
year: 2021
citations: 24
bibkey: liu2021topic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04994'}, {name: Code,
    url: 'https://github.com/Junpliu/ConDigSum}{https://github.com/Junpliu/ConDigSum'}]
tags: [Reinforcement Learning]
---
Unlike well-structured text, such as news reports and encyclopedia articles,
dialogue content often comes from two or more interlocutors, exchanging
information with each other. In such a scenario, the topic of a conversation
can vary upon progression and the key information for a certain topic is often
scattered across multiple utterances of different speakers, which poses
challenges to abstractly summarize dialogues. To capture the various topic
information of a conversation and outline salient facts for the captured
topics, this work proposes two topic-aware contrastive learning objectives,
namely coherence detection and sub-summary generation objectives, which are
expected to implicitly model the topic change and handle information scattering
challenges for the dialogue summarization task. The proposed contrastive
objectives are framed as auxiliary tasks for the primary dialogue summarization
task, united via an alternative parameter updating strategy. Extensive
experiments on benchmark datasets demonstrate that the proposed simple method
significantly outperforms strong baselines and achieves new state-of-the-art
performance. The code and trained models are publicly available via
\href\{https://github.com/Junpliu/ConDigSum\}\{https://github.com/Junpliu/ConDigSum\}.