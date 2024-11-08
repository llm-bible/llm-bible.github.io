---
layout: publication
title: 'Measuring And Benchmarking Large Language Models'' Capabilities To Generate Persuasive Language'
authors: Pauli Amalie Brogaard, Augenstein Isabelle, Assent Ira
conference: "Arxiv"
year: 2024
bibkey: pauli2024measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17753"}
tags: ['Prompting', 'Reinforcement Learning']
---
We are exposed to much information trying to influence us, such as teaser
messages, debates, politically framed news, and propaganda - all of which use
persuasive language. With the recent interest in Large Language Models (LLMs),
we study the ability of LLMs to produce persuasive text. As opposed to prior
work which focuses on particular domains or types of persuasion, we conduct a
general study across various domains to measure and benchmark to what degree
LLMs produce persuasive text - both when explicitly instructed to rewrite text
to be more or less persuasive and when only instructed to paraphrase. To this
end, we construct a new dataset, Persuasive-Pairs, of pairs each consisting of
a short text and of a text rewritten by an LLM to amplify or diminish
persuasive language. We multi-annotate the pairs on a relative scale for
persuasive language. This data is not only a valuable resource in itself, but
we also show that it can be used to train a regression model to predict a score
of persuasive language between text pairs. This model can score and benchmark
new LLMs across domains, thereby facilitating the comparison of different LLMs.
Finally, we discuss effects observed for different system prompts. Notably, we
find that different 'personas' in the system prompt of LLaMA3 change the
persuasive language in the text substantially, even when only instructed to
paraphrase. These findings underscore the importance of investigating
persuasive language in LLM generated text.
