---
layout: publication
title: 'Fine-grained Emotional Paraphrasing Along Emotion Gradients'
authors: Justin Xie
conference: "Arxiv"
year: 2022
bibkey: xie2022fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.03297"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Applications']
---
Paraphrase generation, a.k.a. paraphrasing, is a common and important task in
natural language processing. Emotional paraphrasing, which changes the emotion
embodied in a piece of text while preserving its meaning, has many potential
applications, e.g., moderating online dialogues and preventing cyberbullying.
We introduce a new task of fine-grained emotional paraphrasing along emotion
gradients, that is, altering the emotional intensities of the paraphrases in
fine grain following smooth variations in affective dimensions while preserving
the meanings of the originals. We propose a framework for addressing this task
by fine-tuning text-to-text Transformers through multi-task training. We
enhance several widely used paraphrasing corpus by annotating the input and
target texts with their fine-grained emotion labels. With these labels,
fine-tuning text-to-text Transformers on these corpus entails multi-task
training. Evaluations of the fine-tuned Transformers on separate test sets show
that including fine-grained emotion labels in the paraphrase task significantly
improve the chance of obtaining high-quality paraphrases of the desired
emotions, i.e., more than doubling the number of exact matches of desired
emotions while achieving consistently better scores in paraphrase metrics such
as BLEU, ROGUE, and METEOR.
