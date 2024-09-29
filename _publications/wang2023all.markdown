---
layout: publication
title: All Languages Matter On The Multilingual Safety Of Large Language Models
authors: Wang Wenxuan, Tu Zhaopeng, Chen Chang, Yuan Youliang, Huang Jen-tse, Jiao Wenxiang, Lyu Michael R.
conference: "Arxiv"
year: 2023
bibkey: wang2023all
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00905"}
  - {name: "Code", url: "https://github.com/Jarviswang94/Multilingual_safety_benchmark"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Tools', 'Training Techniques']
---
Safety lies at the core of developing and deploying large language models (LLMs). However previous safety benchmarks only concern the safety in one language e.g. the majority language in the pretraining data such as English. In this work we build the first multilingual safety benchmark for LLMs XSafety in response to the global deployment of LLMs in practice. XSafety covers 14 kinds of commonly used safety issues across 10 languages that span several language families. We utilize XSafety to empirically study the multilingual safety for 4 widely-used LLMs including both close-API and open-source models. Experimental results show that all LLMs produce significantly more unsafe responses for non-English queries than English ones indicating the necessity of developing safety alignment for non-English languages. In addition we propose several simple and effective prompting methods to improve the multilingual safety of ChatGPT by evoking safety knowledge and improving cross-lingual generalization of safety alignment. Our prompting method can significantly reduce the ratio of unsafe responses from 19.137; to 9.737; for non-English queries. We release our data at https://github.com/Jarviswang94/Multilingual\_safety\_benchmark."
