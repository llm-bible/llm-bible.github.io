---
layout: publication
title: 'Large Language Models Memorize Sensor Datasets! Implications On Human Activity Recognition Research'
authors: Harish Haresamudram, Hrudhai Rajasekhar, Nikhil Murlidhar Shanbhogue, Thomas Ploetz
conference: "Arxiv"
year: 2024
bibkey: haresamudram2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.05900'}
tags: ['Training Techniques', 'Model Architecture', 'GPT']
---
The astonishing success of Large Language Models (LLMs) in Natural Language
Processing (NLP) has spurred their use in many application domains beyond text
analysis, including wearable sensor-based Human Activity Recognition (HAR). In
such scenarios, often sensor data are directly fed into an LLM along with text
instructions for the model to perform activity classification. Seemingly
remarkable results have been reported for such LLM-based HAR systems when they
are evaluated on standard benchmarks from the field. Yet, we argue, care has to
be taken when evaluating LLM-based HAR systems in such a traditional way. Most
contemporary LLMs are trained on virtually the entire (accessible) internet --
potentially including standard HAR datasets. With that, it is not unlikely that
LLMs actually had access to the test data used in such benchmark
experiments.The resulting contamination of training data would render these
experimental evaluations meaningless. In this paper we investigate whether LLMs
indeed have had access to standard HAR datasets during training. We apply
memorization tests to LLMs, which involves instructing the models to extend
given snippets of data. When comparing the LLM-generated output to the original
data we found a non-negligible amount of matches which suggests that the LLM
under investigation seems to indeed have seen wearable sensor data from the
benchmark datasets during training. For the Daphnet dataset in particular,
GPT-4 is able to reproduce blocks of sensor readings. We report on our
investigations and discuss potential implications on HAR research, especially
with regards to reporting results on experimental evaluation
