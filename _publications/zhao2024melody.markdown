---
layout: publication
title: 'REFFLY: Melody-constrained Lyrics Editing Model'
authors: Songyan Zhao, Bingxuan Li, Yufei Tian, Nanyun Peng
conference: "Arxiv"
year: 2024
bibkey: zhao2024melody
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00292"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Training Techniques']
---
Automatic melody-to-lyric (M2L) generation aims to create lyrics that align
with a given melody. While most previous approaches generate lyrics from
scratch, revision, editing plain text draft to fit it into the melody, offers a
much more flexible and practical alternative. This enables broad applications,
such as generating lyrics from flexible inputs (keywords, themes, or full text
that needs refining to be singable), song translation (preserving meaning
across languages while keeping the melody intact), or style transfer (adapting
lyrics to different genres). This paper introduces REFFLY (REvision Framework
For LYrics), the first revision framework for editing and generating
melody-aligned lyrics. We train the lyric revision module using our curated
synthesized melody-aligned lyrics dataset, enabling it to transform plain text
into lyrics that align with a given melody. To further enhance the revision
ability, we propose training-free heuristics aimed at preserving both semantic
meaning and musical consistency throughout the editing process. Experimental
results demonstrate the effectiveness of REFFLY across various tasks (e.g.
lyrics generation, song translation), showing that our model outperforms strong
baselines, including Lyra (Tian et al., 2023) and GPT-4, by 25% in both
musicality and text quality.
