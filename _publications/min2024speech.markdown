---
layout: publication
title: 'Speech Retrieval-augmented Generation Without Automatic Speech Recognition'
authors: Do June Min, Karel Mundnich, Andy Lapastora, Erfan Soltanmohammadi, Srikanth Ronanki, Kyu Han
conference: "Arxiv"
year: 2024
bibkey: min2024speech
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.16500'}
tags: ['RAG', 'INTERSPEECH', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
One common approach for question answering over speech data is to first
transcribe speech using automatic speech recognition (ASR) and then employ
text-based retrieval-augmented generation (RAG) on the transcriptions. While
this cascaded pipeline has proven effective in many practical settings, ASR
errors can propagate to the retrieval and generation steps. To overcome this
limitation, we introduce SpeechRAG, a novel framework designed for
open-question answering over spoken data. Our proposed approach fine-tunes a
pre-trained speech encoder into a speech adapter fed into a frozen large
language model (LLM)--based retrieval model. By aligning the embedding spaces
of text and speech, our speech retriever directly retrieves audio passages from
text-based queries, leveraging the retrieval capacity of the frozen text
retriever. Our retrieval experiments on spoken question answering datasets show
that direct speech retrieval does not degrade over the text-based baseline, and
outperforms the cascaded systems using ASR. For generation, we use a speech
language model (SLM) as a generator, conditioned on audio passages rather than
transcripts. Without fine-tuning of the SLM, this approach outperforms cascaded
text-based models when there is high WER in the transcripts.
