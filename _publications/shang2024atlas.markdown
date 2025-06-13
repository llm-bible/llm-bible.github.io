---
layout: publication
title: 'Atlas-chat: Adapting Large Language Models For Low-resource Moroccan Arabic Dialect'
authors: Guokan Shang, Hadi Abdine, Yousef Khoubrane, Amr Mohamed, Yassine Abbahaddou, Sofiane Ennadir, Imane Momayiz, Xuguang Ren, Eric Moulines, Preslav Nakov, Michalis Vazirgiannis, Eric Xing
conference: "Arxiv"
year: 2024
bibkey: shang2024atlas
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17912"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
We introduce Atlas-Chat, the first-ever collection of LLMs specifically
developed for dialectal Arabic. Focusing on Moroccan Arabic, also known as
Darija, we construct our instruction dataset by consolidating existing Darija
language resources, creating novel datasets both manually and synthetically,
and translating English instructions with stringent quality control.
Atlas-Chat-2B, 9B, and 27B models, fine-tuned on the dataset, exhibit superior
ability in following Darija instructions and performing standard NLP tasks.
Notably, our models outperform both state-of-the-art and Arabic-specialized
LLMs like LLaMa, Jais, and AceGPT, e.g., our 9B model gains a 13% performance
boost over a larger 13B model on DarijaMMLU, in our newly introduced evaluation
suite for Darija covering both discriminative and generative tasks.
Furthermore, we perform an experimental analysis of various fine-tuning
strategies and base model choices to determine optimal configurations. All our
resources are publicly accessible, and we believe our work offers comprehensive
design methodologies of instruction-tuning for low-resource languages, which
are often neglected in favor of data-rich languages by contemporary LLMs.
