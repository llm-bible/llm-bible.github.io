---
layout: publication
title: 'CALICO: Conversational Agent Localization Via Synthetic Data Generation'
authors: Andy Rosenbaum, Pegah Kharazmi, Ershad Banijamali, Lu Zeng, Christopher Dipersio, Pan Wei, Gokmen Oz, Clement Chung, Karolina Owczarzak, Fabian Triefenbach, Wael Hamza
conference: "Arxiv"
year: 2024
bibkey: rosenbaum2024conversational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05388"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning']
---
We present CALICO, a method to fine-tune Large Language Models (LLMs) to
localize conversational agent training data from one language to another. For
slots (named entities), CALICO supports three operations: verbatim copy,
literal translation, and localization, i.e. generating slot values more
appropriate in the target language, such as city and airport names located in
countries where the language is spoken. Furthermore, we design an iterative
filtering mechanism to discard noisy generated samples, which we show boosts
the performance of the downstream conversational agent. To prove the
effectiveness of CALICO, we build and release a new human-localized (HL)
version of the MultiATIS++ travel information test set in 8 languages. Compared
to the original human-translated (HT) version of the test set, we show that our
new HL version is more challenging. We also show that CALICO out-performs
state-of-the-art LINGUIST (which relies on literal slot translation out of
context) both on the HT case, where CALICO generates more accurate slot
translations, and on the HL case, where CALICO generates localized slots which
are closer to the HL test set.
