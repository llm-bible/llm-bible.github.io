---
layout: publication
title: A LLM Assisted Exploitation Of Ai45;guardian
authors: Carlini Nicholas
conference: "Arxiv"
year: 2023
bibkey: carlini2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.15008"}
tags: ['GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security']
---
Large language models (LLMs) are now highly capable at a diverse range of tasks. This paper studies whether or not GPT45;4 one such LLM is capable of assisting researchers in the field of adversarial machine learning. As a case study we evaluate the robustness of AI45;Guardian a recent defense to adversarial examples published at IEEE Samp;P 2023 a top computer security conference. We completely break this defense the proposed scheme does not increase robustness compared to an undefended baseline. We write none of the code to attack this model and instead prompt GPT45;4 to implement all attack algorithms following our instructions and guidance. This process was surprisingly effective and efficient with the language model at times producing code from ambiguous instructions faster than the author of this paper could have done. We conclude by discussing (1) the warning signs present in the evaluation that suggested to us AI45;Guardian would be broken and (2) our experience with designing attacks and performing novel research using the most recent advances in language modeling.
