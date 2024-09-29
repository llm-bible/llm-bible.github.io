---
layout: publication
title: Extractgpt Exploring The Potential Of Large Language Models For Product Attribute Value Extraction
authors: Brinkmann Alexander, Shraga Roee, Bizer Christian
conference: "Arxiv"
year: 2023
bibkey: brinkmann2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12537"}
tags: ['BERT', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
In order to facilitate features such as faceted product search and product comparison e45;commerce platforms require accurately structured product data including precise attribute/value pairs. Vendors often times provide unstructured product descriptions consisting only of an offer title and a textual description. Consequently extracting attribute values from titles and descriptions is vital for e45;commerce platforms. State45;of45;the45;art attribute value extraction methods based on pre45;trained language models such as BERT face two drawbacks (i) the methods require significant amounts of task45;specific training data and (ii) the fine45;tuned models have problems with generalising to unseen attribute values that were not part of the training data. This paper explores the potential of using large language models as a more training data45;efficient and more robust alternative to existing AVE methods. We propose prompt templates for describing the target attributes of the extraction to the LLM covering both zero45;shot and few45;shot scenarios. In the zero45;shot scenario textual and JSON45;based target schema representations of the attributes are compared. In the few45;shot scenario we investigate (i) the provision of example attribute values (ii) the selection of in45;context demonstrations (iii) shuffled ensembling to prevent position bias and (iv) fine45;tuning the LLM. We evaluate the prompt templates in combination with hosted LLMs such as GPT45;3.5 and GPT45;4 and open45;source LLMs which can be run locally. We compare the performance of the LLMs to the PLM45;based methods SU45;OpenTag AVEQA and MAVEQA. The highest average F145;score of 8637; was achieved by GPT45;4. Llama45;345;70B performs only 337; worse than GPT45;4 making it a competitive open45;source alternative. Given the same training data this prompt/GPT45;4 combination outperforms the best PLM baseline by an average of 637; F145;score.
