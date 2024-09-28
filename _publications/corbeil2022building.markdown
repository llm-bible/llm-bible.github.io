---
layout: publication
title: Building the Intent Landscape of Real-World Conversational Corpora with Extractive Question-Answering Transformers
authors: Corbeil Jean-philippe, Li Mia Taige, Ghavidel Hadi Abdi
conference: "Arxiv"
year: 2022
bibkey: corbeil2022building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.12886"}
tags: ['ARXIV', 'Applications', 'Prompt', 'Supervised', 'Tools', 'Transformer', 'Unsupervised']
---
For companies with customer service mapping intents inside their conversational data is crucial in building applications based on natural language understanding (NLU). Nevertheless there is no established automated technique to gather the intents from noisy online chats or voice transcripts. Simple clustering approaches are not suited to intent-sparse dialogues. To solve this intent-landscape task we propose an unsupervised pipeline that extracts the intents and the taxonomy of intents from real-world dialogues. Our pipeline mines intent-span candidates with an extractive Question-Answering Electra model and leverages sentence embeddings to apply a low-level density clustering followed by a top-level hierarchical clustering. Our results demonstrate the generalization ability of an ELECTRA large model fine-tuned on the SQuAD2 dataset to understand dialogues. With the right prompting question this model achieves a rate of linguistic validation on intent spans beyond 85. We furthermore reconstructed the intent schemes of five domains from the MultiDoGo dataset with an average recall of 94.3.
