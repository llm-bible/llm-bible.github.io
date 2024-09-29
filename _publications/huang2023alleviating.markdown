---
layout: publication
title: OPERA Alleviating Hallucination In Multi45;modal Large Language Models Via Over45;trust Penalty And Retrospection45;allocation
authors: Qidong Huang, Xiaoyi Dong, Pan Zhang, Bin Wang, Conghui He, Jiaqi Wang, Dahua Lin, Weiming Zhang, Nenghai Yu
conference: "Arxiv"
year: 2023
bibkey: huang2023alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2311.17911v3"}
  - {name: "Code", url: "https://github.com/shikiw/OPERA"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Hallucination posed as a pervasive challenge of multi45;modal large language models (MLLMs) has significantly impeded their real45;world usage that demands precise judgment. Existing methods mitigate this issue with either training with specific designed data or inferencing with external knowledge from other sources incurring inevitable additional costs. In this paper we present OPERA a novel MLLM decoding method grounded in an Over45;trust Penalty and a Retrospection45;Allocation strategy serving as a nearly free lunch to alleviate the hallucination issue without additional data knowledge or training. Our approach begins with an interesting observation that most hallucinations are closely tied to the knowledge aggregation patterns manifested in the self45;attention matrix i.e. MLLMs tend to generate new tokens by focusing on a few summary tokens but not all the previous tokens. Such partial over45;trust inclination results in the neglecting of image tokens and describes the image content with hallucination. Based on the observation OPERA introduces a penalty term on the model logits during the beam45;search decoding to mitigate the over45;trust issue along with a rollback strategy that retrospects the presence of summary tokens in the previously generated tokens and re45;allocate the token selection if necessary. With extensive experiments OPERA shows significant hallucination45;mitigating performance on different MLLMs and metrics proving its effectiveness and generality. Our code is available at https://github.com/shikiw/OPERA.
