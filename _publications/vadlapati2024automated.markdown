---
layout: publication
title: 'Autopuredata: Automated Filtering Of Undesirable Web Data To Update LLM Knowledge'
authors: Praneeth Vadlapati
conference: "Journal of Mathematical Computer Applications 3 (2024) E121"
year: 2024
bibkey: vadlapati2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19271"}
tags: ['Responsible AI', 'RAG', 'Applications']
---
Up-to-date and reliable language models are consistently sought after and are
essential in various applications. Typically, models are trained on a fixed
dataset and then deployed globally. However, the knowledge of the models
becomes outdated. Enabling automatic updation of AI knowledge using web data
involves significant concerns regarding the model's safety and quality due to a
threat from unsafe and undesirable text across the web. The purity of new data
was essential for updating knowledge of language models to maintain their
reliability. This paper proposes AutoPureData, a system that automatically
collects and purifies web data. The system loaded a sample of web data.
Utilizing existing trusted AI models, it successfully eliminated unsafe text
with an accuracy of 97% and undesirable text with an accuracy of 86%,
demonstrating the system's effectiveness in purifying the data. The system
ensures that only meaningful and safe text can be used to update LLM knowledge.
The pure text was then optimized and stored in a vector database for future
querying. It was found that LLM can fetch new data from the vector DB. The LLM
writes the RAG query in English, even if the user's query is in another
language, proving that the system can perform cross-lingual retrieval. This
paper proposes a method to maintain the accuracy and relevance of up-to-date
language models by ensuring that only purified data was used to update LLM
knowledge. This work contributes to updating knowledge of chatbots using
meaningful and safe text, enhancing their utility across various industries,
and potentially reducing the risks associated with outputs caused by unsafe or
impure data. Code is available at github.com/Pro-GenAI/AutoPureData.
