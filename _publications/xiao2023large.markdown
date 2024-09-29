---
layout: publication
title: 'Large Language Models Can Be Good Privacy Protection Learners'
authors: Xiao Yijia, Jin Yiqiao, Bai Yushi, Wu Yue, Yang Xianjun, Luo Xiao, Yu Wenchao, Zhao Xujiang, Liu Yanchi, Chen Haifeng, Wang Wei, Cheng Wei
conference: "Arxiv"
year: 2023
bibkey: xiao2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02469"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
The proliferation of Large Language Models (LLMs) has driven considerable interest in fine-tuning them with domain-specific data to create specialized language models. Nevertheless such domain-specific fine-tuning data often contains sensitive personally identifiable information (PII). Direct fine-tuning LLMs on this data without privacy protection poses a risk of leakage. To address this challenge we introduce Privacy Protection Language Models (PPLM) a novel paradigm for fine-tuning LLMs that effectively injects domain-specific knowledge while safeguarding data privacy. Our work offers a theoretical analysis for model design and delves into various techniques such as corpus curation penalty-based unlikelihood in training loss and instruction-based tuning etc. Extensive experiments across diverse datasets and scenarios demonstrate the effectiveness of our approaches. In particular instruction tuning with both positive and negative examples stands out as a promising method effectively protecting private data while enhancing the models knowledge. Our work underscores the potential for Large Language Models as robust privacy protection learners.
