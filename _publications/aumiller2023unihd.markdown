---
layout: publication
title: 'Unihd At TSAR-2022 Shared Task: Is Compute All We Need For Lexical Simplification?'
authors: Dennis Aumiller, Michael Gertz
conference: "Arxiv"
year: 2023
bibkey: aumiller2023unihd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.01764"}
  - {name: "Code", url: "https://github.com/dennlinger/TSAR-2022-Shared-Task"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Has Code', 'Prompting']
---
Previous state-of-the-art models for lexical simplification consist of
complex pipelines with several components, each of which requires deep
technical knowledge and fine-tuned interaction to achieve its full potential.
As an alternative, we describe a frustratingly simple pipeline based on
prompted GPT-3 responses, beating competing approaches by a wide margin in
settings with few training instances. Our best-performing submission to the
English language track of the TSAR-2022 shared task consists of an ``ensemble''
of six different prompt templates with varying context levels. As a
late-breaking result, we further detail a language transfer technique that
allows simplification in languages other than English. Applied to the Spanish
and Portuguese subset, we achieve state-of-the-art results with only minor
modification to the original prompts. Aside from detailing the implementation
and setup, we spend the remainder of this work discussing the particularities
of prompting and implications for future work. Code for the experiments is
available online at https://github.com/dennlinger/TSAR-2022-Shared-Task
