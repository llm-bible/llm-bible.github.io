---
layout: publication
title: 'Text2tracks: Prompt-based Music Recommendation Via Generative Retrieval'
authors: Enrico Palumbo, Gustavo Penha, Andreas Damianou, José Luis Redondo García, Timothy Christopher Heath, Alice Wang, Hugues Bouchard, Mounia Lalmas
conference: "Arxiv"
year: 2025
bibkey: palumbo2025prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.24193"}
tags: ['GPT', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods', 'Prompting']
---
In recent years, Large Language Models (LLMs) have enabled users to provide
highly specific music recommendation requests using natural language prompts
(e.g. "Can you recommend some old classics for slow dancing?"). In this setup,
the recommended tracks are predicted by the LLM in an autoregressive way, i.e.
the LLM generates the track titles one token at a time. While intuitive, this
approach has several limitation. First, it is based on a general purpose
tokenization that is optimized for words rather than for track titles. Second,
it necessitates an additional entity resolution layer that matches the track
title to the actual track identifier. Third, the number of decoding steps
scales linearly with the length of the track title, slowing down inference. In
this paper, we propose to address the task of prompt-based music recommendation
as a generative retrieval task. Within this setting, we introduce novel,
effective, and efficient representations of track identifiers that
significantly outperform commonly used strategies. We introduce Text2Tracks, a
generative retrieval model that learns a mapping from a user's music
recommendation prompt to the relevant track IDs directly. Through an offline
evaluation on a dataset of playlists with language inputs, we find that (1) the
strategy to create IDs for music tracks is the most important factor for the
effectiveness of Text2Tracks and semantic IDs significantly outperform commonly
used strategies that rely on song titles as identifiers (2) provided with the
right choice of track identifiers, Text2Tracks outperforms sparse and dense
retrieval solutions trained to retrieve tracks from language prompts.
