---
layout: publication
title: A Three45;pronged Approach To Cross45;lingual Adaptation With Multilingual Llms
authors: Singh Vaibhav, Krishna Amrith, Nj Karthika, Ramakrishnan Ganesh
conference: "Arxiv"
year: 2024
bibkey: singh2024three
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17377"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Low45;resource languages by its very definition tend to be under represented in the pre45;training corpora of Large Language Models. In this work we investigate three low45;resource cross45;lingual approaches that enable an LLM adapt to tasks in previously unseen languages. Llama45;2 is an LLM where Indic languages among many other language families contribute to less than 0.00537; of the total 2 trillion token pre45;training corpora. In this work we experiment with the English45;dominated Llama45;2 for cross45;lingual transfer to three Indic languages Bengali Hindi and Tamil as target languages. We study three approaches for cross45;lingual transfer under ICL and fine45;tuning. One we find that adding additional supervisory signals via a dominant language in the LLM leads to improvements both under in45;context learning and fine45;tuning. Two adapting the target languages to word reordering may be beneficial under ICL but its impact diminishes with fine tuning. Finally continued pre45;training in one low45;resource language can improve model performance for other related low45;resource languages.
