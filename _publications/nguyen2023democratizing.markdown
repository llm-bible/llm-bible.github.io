---
layout: publication
title: Democratizing Llms For Low45;resource Languages By Leveraging Their English Dominant Abilities With Linguistically45;diverse Prompts
authors: Nguyen Xuan-phi, Aljunied Sharifah Mahani, Joty Shafiq, Bing Lidong
conference: "Arxiv"
year: 2023
bibkey: nguyen2023democratizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.11372"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Large language models (LLMs) are known to effectively perform tasks by simply observing few exemplars. However in low45;resource languages obtaining such hand45;picked exemplars can still be challenging where unsupervised techniques may be necessary. Moreover competent generative capabilities of LLMs are observed only in high45;resource languages while their performances among under45;represented languages fall behind due to pre45;training data imbalance. To elicit LLMs ability onto low45;resource languages without any supervised data we propose to assemble synthetic exemplars from a diverse set of high45;resource languages to prompt the LLMs to translate from any language into English. These prompts are then used to create intra45;lingual exemplars to perform tasks in the target languages. Our unsupervised prompting method performs on par with supervised few45;shot learning in LLMs of different sizes for translations between English and 13 Indic and 21 African low45;resource languages. We also show that fine45;tuning a 7B model on data generated from our method helps it perform competitively with a 175B model. In non45;English translation tasks our method even outperforms supervised prompting by up to 3 chrF++ in many low45;resource languages. When evaluated on zero45;shot multilingual summarization our method surpasses other English45;pivoting baselines by up to 4 ROUGE45;L and is also favored by GPT45;4.
