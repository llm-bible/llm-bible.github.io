---
layout: publication
title: 'Visfocus: Prompt-guided Vision Encoders For Ocr-free Dense Document Understanding'
authors: Ofir Abramovich, Niv Nayman, Sharon Fogel, Inbal Lavi, Ron Litman, Shahar Tsiper, Royee Tichauer, Srikar Appalaraju, Shai Mazor, R. Manmatha
conference: "Arxiv"
year: 2024
bibkey: abramovich2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12594"}
tags: ['Training Techniques', 'Model Architecture', 'Prompting', 'Pre-Training', 'Attention Mechanism']
---
In recent years, notable advancements have been made in the domain of visual
document understanding, with the prevailing architecture comprising a cascade
of vision and language models. The text component can either be extracted
explicitly with the use of external OCR models in OCR-based approaches, or
alternatively, the vision model can be endowed with reading capabilities in
OCR-free approaches. Typically, the queries to the model are input exclusively
to the language component, necessitating the visual features to encompass the
entire document. In this paper, we present VisFocus, an OCR-free method
designed to better exploit the vision encoder's capacity by coupling it
directly with the language prompt. To do so, we replace the down-sampling
layers with layers that receive the input prompt and allow highlighting
relevant parts of the document, while disregarding others. We pair the
architecture enhancements with a novel pre-training task, using language
masking on a snippet of the document text fed to the visual encoder in place of
the prompt, to empower the model with focusing capabilities. Consequently,
VisFocus learns to allocate its attention to text patches pertinent to the
provided prompt. Our experiments demonstrate that this prompt-guided visual
encoding approach significantly improves performance, achieving
state-of-the-art results on various benchmarks.
