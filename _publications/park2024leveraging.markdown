---
layout: publication
title: Offsetbias Leveraging Debiased Data For Tuning Evaluators
authors: Park Junsoo, Jwa Seungyeon, Ren Meiying, Kim Daeyoung, Choi Sanghyuk
conference: "Arxiv"
year: 2024
bibkey: park2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06551"}
tags: ['Ethics And Bias', 'Prompting', 'RAG', 'Security']
---
Employing Large Language Models (LLMs) to assess the quality of generated responses such as prompting instruct45;tuned models or fine45;tuning judge models has become a widely adopted evaluation method. It is also known that such evaluators are vulnerable to biases such as favoring longer responses. While it is important to overcome this problem the specifics of these biases remain under45;explored. In this work we qualitatively identify six types of biases inherent in various judge models. We propose EvalBiasBench as a meta45;evaluation collection of hand45;crafted test cases for each bias type. Additionally we present de45;biasing dataset construction methods and the associated preference dataset OffsetBias. Experimental results demonstrate that fine45;tuning on our dataset significantly enhances the robustness of judge models against biases and improves performance across most evaluation scenarios. We release our datasets and the fine45;tuned judge model to public.
