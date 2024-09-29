---
layout: publication
title: R45;tuning Instructing Large Language Models To Say `I Dont Know
authors: Zhang Hanning, Diao Shizhe, Lin Yong, Fung Yi R., Lian Qing, Wang Xingyao, Chen Yangyi, Ji Heng, Zhang Tong
conference: "Arxiv"
year: 2023
bibkey: zhang2023r
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09677"}
  - {name: "Code", url: "https://github.com/shizhediao/R&#45;Tuning"}
tags: ['Has Code', 'Pretraining Methods']
---
Large language models (LLMs) have revolutionized numerous domains with their impressive performance but still face their challenges. A predominant issue is the propensity for these models to generate non45;existent facts a concern termed hallucination. Our research is motivated by the observation that previous instruction tuning methods force the model to complete a sentence no matter whether the model knows the knowledge or not. When the question is out of the parametric knowledge it will try to make up something and fail to indicate when it lacks knowledge. In this paper we present a new approach called Refusal45;Aware Instruction Tuning (R45;Tuning). This approach is formalized by first identifying the disparity in knowledge encompassed by pre45;trained parameters compared to that of instruction tuning data. Then we construct the refusal45;aware data based on the knowledge intersection to tune LLMs to refrain from responding to questions beyond its parametric knowledge. Experimental results demonstrate R45;Tuning effectively improves a models ability to answer known questions and refrain from answering unknown questions. Furthermore when tested on out45;of45;domain datasets the refusal ability was found to be a meta45;skill that could be generalized to other tasks. Further analysis surprisingly finds that learning the uncertainty results in better calibration and an improved ability to estimate the uncertainty than uncertainty45;based testing. Our code is available at https://github.com/shizhediao/R&#45;Tuning.
