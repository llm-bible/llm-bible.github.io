---
layout: publication
title: Evaluating The Adversarial Robustness Of Retrieval-based In-context Learning For Large Language Models
authors: Yu Simon Chi Lok, He Jie, Minervini Pasquale, Pan Jeff Z.
conference: "Arxiv"
year: 2024
bibkey: yu2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15984"}
  - {name: "Code", url: "https://github.com/simonucl/adv-retreival-icl"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Has Code', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Security', 'Training Techniques']
---
With the emergence of large language models such as LLaMA and OpenAI GPT-3 In-Context Learning (ICL) gained significant attention due to its effectiveness and efficiency. However ICL is very sensitive to the choice order and verbaliser used to encode the demonstrations in the prompt. Retrieval-Augmented ICL methods try to address this problem by leveraging retrievers to extract semantically related examples as demonstrations. While this approach yields more accurate results its robustness against various types of adversarial attacks including perturbations on test samples demonstrations and retrieved data remains under-explored. Our study reveals that retrieval-augmented models can enhance robustness against test sample attacks outperforming vanilla ICL with a 4.8737; reduction in Attack Success Rate (ASR); however they exhibit overconfidence in the demonstrations leading to a 237; increase in ASR for demonstration attacks. Adversarial training can help improve the robustness of ICL methods to adversarial attacks; however such a training scheme can be too costly in the context of LLMs. As an alternative we introduce an effective training-free adversarial defence method DARD which enriches the example pool with those attacked samples. We show that DARD yields improvements in performance and robustness achieving a 1537; reduction in ASR over the baselines. Code and data are released to encourage further research https://github.com/simonucl/adv-retreival-icl
