---
layout: publication
title: Automatic Generation Of Multiple45;choice Questions
authors: Zhang Cheng
conference: "Arxiv"
year: 2023
bibkey: zhang2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.14576"}
tags: ['Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Creating multiple45;choice questions to assess reading comprehension of a given article involves generating question45;answer pairs (QAPs) and adequate distractors. We present two methods to tackle the challenge of QAP generations (1) A deep45;learning45;based end45;to45;end question generation system based on T5 Transformer with Preprocessing and Postprocessing Pipelines (TP3). We use the finetuned T5 model for our downstream task of question generation and improve accuracy using a combination of various NLP tools and algorithms in preprocessing and postprocessing to select appropriate answers and filter undesirable questions. (2) A sequence45;learning45;based scheme to generate adequate QAPs via meta45;sequence representations of sentences. A meta45;sequence is a sequence of vectors comprising semantic and syntactic tags. we devise a scheme called MetaQA to learn meta sequences from training data to form pairs of a meta sequence for a declarative sentence and a corresponding interrogative sentence. The TP3 works well on unseen data which is complemented by MetaQA. Both methods can generate well45;formed and grammatically correct questions. Moreover we present a novel approach to automatically generate adequate distractors for a given QAP. The method is a combination of part45;of45;speech tagging named45;entity tagging semantic45;role labeling regular expressions domain knowledge bases word embeddings word edit distance WordNet and other algorithms.
