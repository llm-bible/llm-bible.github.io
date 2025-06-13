---
layout: publication
title: 'Real-time Textless Dialogue Generation'
authors: Long Mai, Julie Carson-berndsen
conference: "Arxiv"
year: 2025
bibkey: mai2025real
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.04877'}
  - {name: "Code", url: 'https://github.com/mailong25/rts2s-dg'}
tags: ['Reinforcement Learning', 'Has Code', 'Applications']
---
Recent advancements in large language models (LLMs) have led to significant
progress in text-based dialogue systems. These systems can now generate
high-quality responses that are accurate and coherent across a wide range of
topics and tasks. However, spoken dialogue systems still lag behind in terms of
naturalness. They tend to produce robotic interactions, with issues such as
slow response times, overly generic or cautious replies, and a lack of natural
rhythm and fluid turn-taking. This shortcoming is largely due to the
over-reliance on the traditional cascaded design, which involve separate,
sequential components, as well as the use of text as an intermediate
representation. This paper propose a real-time, textless spoken dialogue
generation model (RTTL-DG) that aims to overcome these challenges. Our system
enables fluid turn-taking and generates responses with minimal delay by
processing streaming spoken conversation directly. Additionally, our model
incorporates backchannels, filters, laughter, and other paralinguistic signals,
which are often absent in cascaded dialogue systems, to create more natural and
human-like interactions. The implementations and generated samples are
available in our repository: https://github.com/mailong25/rts2s-dg
