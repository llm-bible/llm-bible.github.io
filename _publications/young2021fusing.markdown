---
layout: publication
title: Fusing Task-oriented And Open-domain Dialogues In Conversational Agents
authors: Tom Young, Frank Xing, Vlad Pandelea, Jinjie Ni, Erik Cambria
conference: Published at AAAI 2022
year: 2021
citations: 25
bibkey: young2021fusing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04137'}, {name: Code,
    url: 'https://github.com/tomyoung903/FusedChat'}]
tags: [Agentic]
---
The goal of building intelligent dialogue systems has largely been separately
pursued under two paradigms: task-oriented dialogue (TOD) systems, which
perform goal-oriented functions, and open-domain dialogue (ODD) systems, which
focus on non-goal-oriented chitchat. The two dialogue modes can potentially be
intertwined together seamlessly in the same conversation, as easily done by a
friendly human assistant. Such ability is desirable in conversational agents,
as the integration makes them more accessible and useful. Our paper addresses
this problem of fusing TODs and ODDs in multi-turn dialogues. Based on the
popular TOD dataset MultiWOZ, we build a new dataset FusedChat, by rewriting
the existing TOD turns and adding new ODD turns. This procedure constructs
conversation sessions containing exchanges from both dialogue modes. It
features inter-mode contextual dependency, i.e., the dialogue turns from the
two modes depend on each other. Rich dependency patterns including co-reference
and ellipsis are features. The new dataset, with 60k new human-written ODD
turns and 5k re-written TOD turns, offers a benchmark to test a dialogue
model's ability to perform inter-mode conversations. This is a more challenging
task since the model has to determine the appropriate dialogue mode and
generate the response based on the inter-mode context. But such models would
better mimic human-level conversation capabilities. We evaluate baseline models
on this task, including classification-based two-stage models and two-in-one
fused models. We publicly release FusedChat and the baselines to propel future
work on inter-mode dialogue systems https://github.com/tomyoung903/FusedChat.