---
layout: publication
title: 'Babywalk: Going Farther In Vision-and-language Navigation By Taking Baby Steps'
authors: Wang Zhu et al.
conference: Arxiv
year: 2020
citations: 23
bibkey: zhu2020going
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.04625'}, {name: Code,
    url: 'https://github.com/Sha-Lab/babywalk'}]
tags: [Reinforcement Learning, Agentic]
---
Learning to follow instructions is of fundamental importance to autonomous
agents for vision-and-language navigation (VLN). In this paper, we study how an
agent can navigate long paths when learning from a corpus that consists of
shorter ones. We show that existing state-of-the-art agents do not generalize
well. To this end, we propose BabyWalk, a new VLN agent that is learned to
navigate by decomposing long instructions into shorter ones (BabySteps) and
completing them sequentially. A special design memory buffer is used by the
agent to turn its past experiences into contexts for future steps. The learning
process is composed of two phases. In the first phase, the agent uses imitation
learning from demonstration to accomplish BabySteps. In the second phase, the
agent uses curriculum-based reinforcement learning to maximize rewards on
navigation tasks with increasingly longer instructions. We create two new
benchmark datasets (of long navigation tasks) and use them in conjunction with
existing ones to examine BabyWalk's generalization ability. Empirical results
show that BabyWalk achieves state-of-the-art results on several metrics, in
particular, is able to follow long instructions better. The codes and the
datasets are released on our project page https://github.com/Sha-Lab/babywalk.