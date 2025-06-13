---
layout: publication
title: 'OLAPH: Improving Factuality In Biomedical Long-form Question Answering'
authors: Minbyul Jeong, Hyeon Hwang, Chanwoong Yoon, Taewhoo Lee, Jaewoo Kang
conference: "Arxiv"
year: 2024
bibkey: jeong2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12701"}
tags: ['Applications', 'Training Techniques', 'Language Modeling', 'Tools']
---
In the medical domain, numerous scenarios necessitate the long-form
generation ability of large language models (LLMs). Specifically, when
addressing patients' questions, it is essential that the model's response
conveys factual claims, highlighting the need for an automated method to
evaluate those claims. Thus, we introduce MedLFQA, a benchmark dataset
reconstructed using long-form question-answering datasets related to the
biomedical domain. We use MedLFQA to facilitate a cost-effective automatic
evaluations of factuality. We also propose OLAPH, a simple and novel framework
that utilizes cost-effective and multifaceted automatic evaluation to construct
a synthetic preference set and answers questions in our preferred manner. Our
framework leads us to train LLMs step-by-step to reduce hallucinations and
include crucial medical claims. We highlight that, even on evaluation metrics
not used during training, LLMs trained with our OLAPH framework demonstrate
significant performance improvement in factuality. Our findings reveal that a
7B LLM trained with our OLAPH framework can provide long answers comparable to
the medical experts' answers in terms of factuality. We believe that our work
could shed light on gauging the long-text generation ability of LLMs in the
medical domain. Our code and datasets are available.
