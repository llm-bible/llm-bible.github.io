---
layout: publication
title: Offsetbias Leveraging Debiased Data For Tuning Evaluators
authors: Park Junsoo, Jwa Seungyeon, Ren Meiying, Kim Daeyoung, Choi Sanghyuk
conference: "Arxiv"
year: 2024
bibkey: park2024offsetbias
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06551"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Security', 'Training Techniques']
---
Employing Large Language Models (LLMs) to assess the quality of generated responses such as prompting instruct-tuned models or fine-tuning judge models has become a widely adopted evaluation method. It is also known that such evaluators are vulnerable to biases such as favoring longer responses. While it is important to overcome this problem the specifics of these biases remain under-explored. In this work we qualitatively identify six types of biases inherent in various judge models. We propose EvalBiasBench as a meta-evaluation collection of hand-crafted test cases for each bias type. Additionally we present de-biasing dataset construction methods and the associated preference dataset OffsetBias. Experimental results demonstrate that fine-tuning on our dataset significantly enhances the robustness of judge models against biases and improves performance across most evaluation scenarios. We release our datasets and the fine-tuned judge model to public.
