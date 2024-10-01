---
layout: publication
title: 'The Missing Ingredient In Zero-shot Neural Machine Translation'
authors: Arivazhagan Naveen, Bapna Ankur, Firat Orhan, Aharoni Roee, Johnson Melvin, Macherey Wolfgang
conference: "Arxiv"
year: 2019
bibkey: arivazhagan2019missing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1903.07091"}
tags: ['Applications', 'Training Techniques']
---
"Multilingual Neural Machine Translation (NMT) models are capable of translating between multiple source and target languages. Despite various approaches to train such models, they have difficulty with zero-shot translation: translating between language pairs that were not together seen during training. In this paper we first diagnose why state-of-the-art multilingual NMT models that rely purely on parameter sharing, fail to generalize to unseen language pairs. We then propose auxiliary losses on the NMT encoder that impose representational invariance across languages. Our simple approach vastly improves zero-shot translation quality without regressing on supervised directions. For the first time, on WMT14 English-FrenchGerman, we achieve zero-shot performance that is on par with pivoting. We also demonstrate the easy scalability of our approach to multiple languages on the IWSLT 2017 shared task."
