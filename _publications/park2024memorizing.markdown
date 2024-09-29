---
layout: publication
title: Memorizing Documents With Guidance In Large Language Models
authors: Park Bumjin, Choi Jaesik
conference: "Arxiv"
year: 2024
bibkey: park2024memorizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15996"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Training data plays a pivotal role in AI models. Large language models (LLMs) are trained with massive amounts of documents and their parameters hold document45;related contents. Recently several studies identified content45;specific locations in LLMs by examining the parameters. Instead of the post hoc interpretation we propose another approach. We propose document45;wise memory architecture to track document memories in training. The proposed architecture maps document representations to memory entries which softly mask memories in the forward process of LLMs. Additionally we propose document guidance loss which increases the likelihood of text with document memories and reduces the likelihood of the text with the memories of other documents. Experimental results on Wikitext45;10345;v1 with Pythia45;1B show that the proposed methods provide different memory entries for documents and high recall of document45;related content in generation with trained document45;wise memories.
