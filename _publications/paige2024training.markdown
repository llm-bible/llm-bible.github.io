---
layout: publication
title: Training LLMs to Recognize Hedges in Spontaneous Narratives
authors: Paige Amie J., Soubki Adil, Murzaku John, Rambow Owen, Brennan Susan E.
conference: "SIGDIAL"
year: 2024
bibkey: paige2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03319"}
tags: ['BERT', 'Few Shot', 'Fine Tuning', 'GPT', 'In Context Learning', 'LLM', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Hedges allow speakers to mark utterances as provisional whether to signal non-prototypicality or fuzziness to indicate a lack of commitment to an utterance to attribute responsibility for a statement to someone else to invite input from a partner or to soften critical feedback in the service of face-management needs. Here we focus on hedges in an experimentally parameterized corpus of 63 Roadrunner cartoon narratives spontaneously produced from memory by 21 speakers for co-present addressees transcribed to text (Galati and Brennan 2010). We created a gold standard of hedges annotated by human coders (the Roadrunner-Hedge corpus) and compared three LLM-based approaches for hedge detection fine-tuning BERT and zero and few-shot prompting with GPT-4o and LLaMA-3. The best-performing approach was a fine-tuned BERT model followed by few-shot GPT-4o. After an error analysis on the top performing approaches we used an LLM-in-the-Loop approach to improve the gold standard coding as well as to highlight cases in which hedges are ambiguous in linguistically interesting ways that will guide future research. This is the first step in our research program to train LLMs to interpret and generate collateral signals appropriately and meaningfully in conversation.
