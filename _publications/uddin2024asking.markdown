---
layout: publication
title: Asking and Answering Questions to Extract Event-Argument Structures
authors: Uddin Md Nayem, George Enfa Rose, Blanco Eduardo, Corman Steven
conference: "Arxiv"
year: 2024
bibkey: uddin2024asking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16413"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
This paper presents a question-answering approach to extract document-level event-argument structures. We automatically ask and answer questions for each argument type an event may have. Questions are generated using manually defined templates and generative transformers. Template-based questions are generated using predefined role-specific wh-words and event triggers from the context document. Transformer-based questions are generated using large language models trained to formulate questions based on a passage and the expected answer. Additionally we develop novel data augmentation strategies specialized in inter-sentential event-argument relations. We use a simple span-swapping technique coreference resolution and large language models to augment the training instances. Our approach enables transfer learning without any corpora-specific modifications and yields competitive results with the RAMS dataset. It outperforms previous work and it is especially beneficial to extract arguments that appear in different sentences than the event trigger. We also present detailed quantitative and qualitative analyses shedding light on the most common errors made by our best model.
