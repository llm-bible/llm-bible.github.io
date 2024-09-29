---
layout: publication
title: What BERT Based Language Models Learn In Spoken Transcripts An Empirical Study
authors: Kumar Ayush, Sundararaman Mukuntha Narayanan, Vepa Jithendra
conference: "Arxiv"
year: 2021
bibkey: kumar2021what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.09105"}
tags: ['BERT', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques']
---
Language Models (LMs) have been ubiquitously leveraged in various tasks including spoken language understanding (SLU). Spoken language requires careful understanding of speaker interactions dialog states and speech induced multimodal behaviors to generate a meaningful representation of the conversation. In this work we propose to dissect SLU into three representative propertiesconversational (disfluency pause overtalk) channel (speaker45;type turn45;tasks) and ASR (insertion deletionsubstitution). We probe BERT based language models (BERT RoBERTa) trained on spoken transcripts to investigate its ability to understand multifarious properties in absence of any speech cues. Empirical results indicate that LM is surprisingly good at capturing conversational properties such as pause prediction and overtalk detection from lexical tokens. On the downsides the LM scores low on turn45;tasks and ASR errors predictions. Additionally pre45;training the LM on spoken transcripts restrain its linguistic understanding. Finally we establish the efficacy and transferability of the mentioned properties on two benchmark datasets Switchboard Dialog Act and Disfluency datasets.
