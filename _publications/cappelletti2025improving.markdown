---
layout: publication
title: 'Improving LLM First-token Predictions In Multiple-choice Question Answering Via Prefilling Attack'
authors: Silvia Cappelletti, Tobia Poppi, Samuele Poppi, Zheng-xin Yong, Diego Garcia-olano, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara
conference: "Arxiv"
year: 2025
bibkey: cappelletti2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15323"}
tags: ['Responsible AI', 'RAG', 'Security', 'Applications']
---
Large Language Models (LLMs) are increasingly evaluated on multiple-choice question answering (MCQA) tasks using *first-token probability* (FTP), which selects the answer option whose initial token has the highest likelihood. While efficient, FTP can be fragile: models may assign high probability to unrelated tokens (*misalignment*) or use a valid token merely as part of a generic preamble rather than as a clear answer choice (*misinterpretation*), undermining the reliability of symbolic evaluation. We propose a simple solution: the *prefilling attack*, a structured natural-language prefix (e.g., "*The correct option is:*") prepended to the model output. Originally explored in AI safety, we repurpose prefilling to steer the model to respond with a clean, valid option, without modifying its parameters. Empirically, the FTP with prefilling strategy substantially improves accuracy, calibration, and output consistency across a broad set of LLMs and MCQA benchmarks. It outperforms standard FTP and often matches the performance of open-ended generation approaches that require full decoding and external classifiers, while being significantly more efficient. Our findings suggest that prefilling is a simple, robust, and low-cost method to enhance the reliability of FTP-based evaluation in multiple-choice settings.
