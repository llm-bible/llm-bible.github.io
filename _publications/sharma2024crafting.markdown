---
layout: publication
title: 'Crafting Narrative Closures: Zero-shot Learning With SSM Mamba For Short Story Ending Generation'
authors: Divyam Sharma, Divya Santhanam
conference: "Arxiv"
year: 2024
bibkey: sharma2024crafting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10848'}
tags: ['GPT', 'BERT', 'Prompting', 'Model Architecture']
---
Writing stories is an engaging yet challenging endeavor. Often, authors
encounter moments of creative block, where the path forward in their narrative
becomes obscured. This paper is designed to address such moments by providing
an innovative solution: A tool that completes stories based on given prompts.
By inputting a short story prompt, users can receive a conclusion to their
story, articulated in one sentence or more, thereby enhancing the storytelling
process with AI-driven creativity. This tool aims not only to assist authors in
navigating writer's block but also to offer a fun and interactive way for
anyone to expand on story ideas spontaneously. Through this paper, we explore
the intersection of artificial intelligence and creative writing, pushing the
boundaries of how stories can be crafted and concluded. To create our final
text-generation models, we used a pre-trained GPT-3.5 model and a newly created
finetuned SSM-Mamba model, both of which perform well on a comprehensive list
of metrics including BERT score, METEOR, BLEU, ROUGE, and Perplexity. The SSM
model has also been made public for the NLP community on HuggingFace models as
an open source contribution, which for the timebeing is a first of its kind
state-space model for story-generation task on HuggingFace.
