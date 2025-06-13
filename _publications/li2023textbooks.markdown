---
layout: publication
title: 'Textbooks Are All You Need II: Phi-1.5 Technical Report'
authors: Yuanzhi Li, Sébastien Bubeck, Ronen Eldan, Allie Del Giorno, Suriya Gunasekar, Yin Tat Lee
conference: "Arxiv"
year: 2023
bibkey: li2023textbooks
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.05463'}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Prompting', 'Ethics and Bias', 'In-Context Learning', 'Pretraining Methods']
---
We continue the investigation into the power of smaller Transformer-based
language models as initiated by \textbf\{TinyStories\} -- a 10 million parameter
model that can produce coherent English -- and the follow-up work on
\textbf\{phi-1\}, a 1.3 billion parameter model with Python coding performance
close to the state-of-the-art. The latter work proposed to use existing Large
Language Models (LLMs) to generate ``textbook quality" data as a way to enhance
the learning process compared to traditional web data. We follow the
``Textbooks Are All You Need" approach, focusing this time on common sense
reasoning in natural language, and create a new 1.3 billion parameter model
named \textbf\{phi-1.5\}, with performance on natural language tasks comparable
to models 5x larger, and surpassing most non-frontier LLMs on more complex
reasoning tasks such as grade-school mathematics and basic coding. More
generally, \textbf\{phi-1.5\} exhibits many of the traits of much larger LLMs,
both good -- such as the ability to ``think step by step" or perform some
rudimentary in-context learning -- and bad, including hallucinations and the
potential for toxic and biased generations -- encouragingly though, we are
seeing improvement on that front thanks to the absence of web data. We
open-source \textbf\{phi-1.5\} to promote further research on these urgent
topics.
