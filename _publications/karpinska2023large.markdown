---
layout: publication
title: Large Language Models Effectively Leverage Document-level Context For Literary Translation But Critical Errors Persist
authors: Karpinska Marzena, Iyyer Mohit
conference: "Arxiv"
year: 2023
bibkey: karpinska2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.03245"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Large language models (LLMs) are competitive with the state of the art on a wide range of sentence-level translation datasets. However their ability to translate paragraphs and documents remains unexplored because evaluation in these settings is costly and difficult. We show through a rigorous human evaluation that asking the Gpt-3.5 (text-davinci-003) LLM to translate an entire literary paragraph (e.g. from a novel) at once results in higher-quality translations than standard sentence-by-sentence translation across 18 linguistically-diverse language pairs (e.g. translating into and out of Japanese Polish and English). Our evaluation which took approximately 350 hours of effort for annotation and analysis is conducted by hiring translators fluent in both the source and target language and asking them to provide both span-level error annotations as well as preference judgments of which systems translations are better. We observe that discourse-level LLM translators commit fewer mistranslations grammar errors and stylistic inconsistencies than sentence-level approaches. With that said critical errors still abound including occasional content omissions and a human translators intervention remains necessary to ensure that the authors voice remains intact. We publicly release our dataset and error annotations to spur future research on evaluation of document-level literary translation.
