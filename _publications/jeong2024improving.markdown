---
layout: publication
title: 'OLAPH: Improving Factuality In Biomedical Long-form Question Answering'
authors: Jeong Minbyul, Hwang Hyeon, Yoon Chanwoong, Lee Taewhoo, Kang Jaewoo
conference: "Arxiv"
year: 2024
bibkey: jeong2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12701"}
  - {name: "Code", url: "https://github.com/dmis-lab/OLAPH}{https://github.com/dmis-lab/OLAPH"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Language Modeling', 'Tools', 'Training Techniques']
---
In the medical domain, numerous scenarios necessitate the long-form generation ability of large language models (LLMs). Specifically, when addressing patients' questions, it is essential that the model's response conveys factual claims, highlighting the need for an automated method to evaluate those claims. Thus, we introduce MedLFQA, a benchmark dataset reconstructed using long-form question-answering datasets related to the biomedical domain. We use MedLFQA to facilitate the automatic evaluations of factuality. We also propose OLAPH, a simple and novel framework that enables the improvement of factuality through automatic evaluations. The OLAPH framework iteratively trains LLMs to mitigate hallucinations using sampling predictions and preference optimization. In other words, we iteratively set the highest-scoring response as a preferred response derived from sampling predictions and train LLMs to align with the preferred response that improves factuality. We highlight that, even on evaluation metrics not used during training, LLMs trained with our OLAPH framework demonstrate significant performance improvement in factuality. Our findings reveal that a 7B LLM trained with our OLAPH framework can provide long answers comparable to the medical experts' answers in terms of factuality. We believe that our work could shed light on gauging the long-text generation ability of LLMs in the medical domain. Our code and datasets are available at https://github.com/dmis-lab/OLAPH\}\{https://github.com/dmis-lab/OLAPH.
