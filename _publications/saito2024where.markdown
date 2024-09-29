---
layout: publication
title: 'Where Is The Answer? Investigating Positional Bias In Language Model Knowledge Extraction'
authors: Saito Kuniaki, Sohn Kihyuk, Lee Chen-yu, Ushiku Yoshitaka
conference: "Arxiv"
year: 2024
bibkey: saito2024where
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12170"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Large language models require updates to remain up-to-date or adapt to new domains by fine-tuning them with new documents. One key is memorizing the latest information in a way that the memorized information is extractable with a query prompt. However LLMs suffer from a phenomenon called perplexity curse; despite minimizing document perplexity during fine-tuning LLMs struggle to extract information through a prompt sentence. In this new knowledge acquisition and extraction we find a very intriguing fact that LLMs can accurately answer questions about the first sentence but they struggle to extract information described in the middle or end of the documents used for fine-tuning. Our study suggests that the auto-regressive training causes this issue; each token is prompted by reliance on all previous tokens which hinders the model from recalling information from training documents by question prompts. To conduct the in-depth study we publish both synthetic and real datasets enabling the evaluation of the QA performance w.r.t. the position of the corresponding answer in a document. Our investigation shows that even a large model suffers from the perplexity curse but regularization such as denoising auto-regressive loss can enhance the information extraction from diverse positions. These findings will be (i) a key to improving knowledge extraction from LLMs and (ii) new elements to discuss the trade-off between RAG and fine-tuning in adapting LLMs to a new domain.
