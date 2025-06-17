---
layout: publication
title: 'An Image Is Worth One Word: Personalizing Text-to-image Generation Using Textual
  Inversion'
authors: Rinon Gal et al.
conference: Arxiv
year: 2022
citations: 322
bibkey: gal2022image
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.01618'}, {name: Code,
    url: 'https://textual-inversion.github.io'}]
tags: [Applications]
---
Text-to-image models offer unprecedented freedom to guide creation through
natural language. Yet, it is unclear how such freedom can be exercised to
generate images of specific unique concepts, modify their appearance, or
compose them in new roles and novel scenes. In other words, we ask: how can we
use language-guided models to turn our cat into a painting, or imagine a new
product based on our favorite toy? Here we present a simple approach that
allows such creative freedom. Using only 3-5 images of a user-provided concept,
like an object or a style, we learn to represent it through new "words" in the
embedding space of a frozen text-to-image model. These "words" can be composed
into natural language sentences, guiding personalized creation in an intuitive
way. Notably, we find evidence that a single word embedding is sufficient for
capturing unique and varied concepts. We compare our approach to a wide range
of baselines, and demonstrate that it can more faithfully portray the concepts
across a range of applications and tasks.
  Our code, data and new words will be available at:
https://textual-inversion.github.io