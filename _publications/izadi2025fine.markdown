---
layout: publication
title: 'Fine-grained Alignment And Noise Refinement For Compositional Text-to-image Generation'
authors: Amir Mohammad Izadi, Seyed Mohammad Hadi Hosseini, Soroush Vafaie Tabar, Ali Abdollahi, Armin Saghafian, Mahdieh Soleymani Baghshah
conference: "Arxiv"
year: 2025
bibkey: izadi2025fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06506"}
  - {name: "Code", url: "https://github.com/hadi-hosseini/noise-refinement"}
tags: ['Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Prompting']
---
Text-to-image generative models have made significant advancements in recent
years; however, accurately capturing intricate details in textual prompts, such
as entity missing, attribute binding errors, and incorrect relationships
remains a formidable challenge. In response, we present an innovative,
training-free method that directly addresses these challenges by incorporating
tailored objectives to account for textual constraints. Unlike layout-based
approaches that enforce rigid structures and limit diversity, our proposed
approach offers a more flexible arrangement of the scene by imposing just the
extracted constraints from the text, without any unnecessary additions. These
constraints are formulated as losses-entity missing, entity mixing, attribute
binding, and spatial relationships, integrated into a unified loss that is
applied in the first generation stage. Furthermore, we introduce a
feedback-driven system for fine-grained initial noise refinement. This system
integrates a verifier that evaluates the generated image, identifies
inconsistencies, and provides corrective feedback. Leveraging this feedback,
our refinement method first targets the unmet constraints by refining the
faulty attention maps caused by initial noise, through the optimization of
selective losses associated with these constraints. Subsequently, our unified
loss function is reapplied to proceed the second generation phase. Experimental
results demonstrate that our method, relying solely on our proposed objective
functions, significantly enhances compositionality, achieving a 24% improvement
in human evaluation and a 25% gain in spatial relationships. Furthermore, our
fine-grained noise refinement proves effective, boosting performance by up to
5%. Code is available at https://github.com/hadi-hosseini/noise-refinement.
