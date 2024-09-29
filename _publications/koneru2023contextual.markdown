---
layout: publication
title: Contextual Refinement Of Translations&#58; Large Language Models For Sentence And Document-level Post-editing
authors: Koneru Sai, Exel Miriam, Huck Matthias, Niehues Jan
conference: "Arxiv"
year: 2023
bibkey: koneru2023contextual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14855"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated considerable success in various Natural Language Processing tasks but they have yet to attain state-of-the-art performance in Neural Machine Translation (NMT). Nevertheless their significant performance in tasks demanding a broad understanding and contextual processing shows their potential for translation. To exploit these abilities we investigate using LLMs for MT and explore recent parameter-efficient fine-tuning techniques. Surprisingly our initial experiments find that fine-tuning for translation purposes even led to performance degradation. To overcome this we propose an alternative approach adapting LLMs as Automatic Post-Editors (APE) rather than direct translators. Building on the LLMs exceptional ability to process and generate lengthy sequences we also propose extending our approach to document-level translation. We show that leveraging Low-Rank-Adapter fine-tuning for APE can yield significant improvements across both sentence and document-level metrics while generalizing to out-of-domain data. Most notably we achieve a state-of-the-art accuracy rate of 8937; on the ContraPro test set which specifically assesses the models ability to resolve pronoun ambiguities when translating from English to German. Lastly we investigate a practical scenario involving manual post-editing for document-level translation where reference context is made available. Here we demonstrate that leveraging human corrections can significantly reduce the number of edits required for subsequent translations (Interactive Demo for integrating manual feedback can be found here https://huggingface.co/spaces/skoneru/contextual\_refinement\_ende)."
