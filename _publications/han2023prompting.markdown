---
layout: publication
title: Pive Prompting With Iterative Verification Improving Graph45;based Generative Capability Of Llms
authors: Han Jiuzhou, Collier Nigel, Buntine Wray, Shareghi Ehsan
conference: "Arxiv"
year: 2023
bibkey: han2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12392"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have shown great abilities of solving various natural language tasks in different domains. Due to the training objective of LLMs and their pre45;training data LLMs are not very well equipped for tasks involving structured data generation. We propose a framework Prompting with Iterative Verification (PiVe) to improve graph45;based generative capability of LLMs. We show how a small language model could be trained to act as a verifier module for the output of an LLM~(i.e. ChatGPT GPT45;4) and to iteratively improve its performance via fine45;grained corrective instructions. We also show how the verifier module could apply iterative corrections offline for a more cost45;effective solution to the text45;to45;graph generation task. Experiments on three graph45;based datasets show consistent improvement gained via PiVe. Additionally we create GenWiki45;HIQ and highlight that the verifier module can be used as a data augmentation tool to help improve the quality of automatically generated parallel text45;graph datasets.
