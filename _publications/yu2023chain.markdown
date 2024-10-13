---
layout: publication
title: 'Chain-of-note: Enhancing Robustness In Retrieval-augmented Language Models'
authors: Yu Wenhao, Zhang Hongming, Pan Xiaoman, Ma Kaixin, Wang Hongwei, Yu Dong
conference: "Arxiv"
year: 2023
bibkey: yu2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09210"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Retrieval-augmented language models (RALMs) represent a substantial
advancement in the capabilities of large language models, notably in reducing
factual hallucination by leveraging external knowledge sources. However, the
reliability of the retrieved information is not always guaranteed. The
retrieval of irrelevant data can lead to misguided responses, and potentially
causing the model to overlook its inherent knowledge, even when it possesses
adequate information to address the query. Moreover, standard RALMs often
struggle to assess whether they possess adequate knowledge, both intrinsic and
retrieved, to provide an accurate answer. In situations where knowledge is
lacking, these systems should ideally respond with "unknown" when the answer is
unattainable. In response to these challenges, we introduces Chain-of-Noting
(CoN), a novel approach aimed at improving the robustness of RALMs in facing
noisy, irrelevant documents and in handling unknown scenarios. The core idea of
CoN is to generate sequential reading notes for retrieved documents, enabling a
thorough evaluation of their relevance to the given question and integrating
this information to formulate the final answer. We employed ChatGPT to create
training data for CoN, which was subsequently trained on an LLaMa-2 7B model.
Our experiments across four open-domain QA benchmarks show that RALMs equipped
with CoN significantly outperform standard RALMs. Notably, CoN achieves an
average improvement of +7.9 in EM score given entirely noisy retrieved
documents and +10.5 in rejection rates for real-time questions that fall
outside the pre-training knowledge scope.
