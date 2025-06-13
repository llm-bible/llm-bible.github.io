---
layout: publication
title: 'Probing Audio-generation Capabilities Of Text-based Language Models'
authors: Arjun Prasaath Anbazhagan, Parteek Kumar, Ujjwal Kaur, Aslihan Akalin, Kevin Zhu, Sean O'brien
conference: "Arxiv"
year: 2025
bibkey: anbazhagan2025probing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00003'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting', 'Training Techniques']
---
How does textual representation of audio relate to the Large Language Model's (LLMs) learning about the audio world? This research investigates the extent to which LLMs can be prompted to generate audio, despite their primary training in textual data. We employ a three-tier approach, progressively increasing the complexity of audio generation: 1) Musical Notes, 2) Environmental Sounds, and 3) Human Speech. To bridge the gap between text and audio, we leverage code as an intermediary, prompting LLMs to generate code that, when executed, produces the desired audio output. To evaluate the quality and accuracy of the generated audio, we employ FAD and CLAP scores. Our findings reveal that while LLMs can generate basic audio features, their performance deteriorates as the complexity of the audio increases. This suggests that while LLMs possess a latent understanding of the auditory world, their ability to translate this understanding into tangible audio output remains rudimentary. Further research into techniques that can enhance the quality and diversity of LLM-generated audio can lead to an improvement in the performance of text-based LLMs in generating audio.
