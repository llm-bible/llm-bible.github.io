---
layout: publication
title: 'Text2midi-inferalign: Improving Symbolic Music Generation With Inference-time Alignment'
authors: Abhinaba Roy, Geeta Puri, Dorien Herremans
conference: "Arxiv"
year: 2025
bibkey: roy2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12669"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
We present Text2midi-InferAlign, a novel technique for improving symbolic music generation at inference time. Our method leverages text-to-audio alignment and music structural alignment rewards during inference to encourage the generated music to be consistent with the input caption. Specifically, we introduce two objectives scores: a text-audio consistency score that measures rhythmic alignment between the generated music and the original text caption, and a harmonic consistency score that penalizes generated music containing notes inconsistent with the key. By optimizing these alignment-based objectives during the generation process, our model produces symbolic music that is more closely tied to the input captions, thereby improving the overall quality and coherence of the generated compositions. Our approach can extend any existing autoregressive model without requiring further training or fine-tuning. We evaluate our work on top of Text2midi - an existing text-to-midi generation model, demonstrating significant improvements in both objective and subjective evaluation metrics.
