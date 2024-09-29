---
layout: publication
title: LLM Aided Semi45;supervision For Extractive Dialog Summarization
authors: Mishra Nishant, Sahu Gaurav, Calixto Iacer, Abu-hanna Ameen, Laradji Issam H.
conference: "Arxiv"
year: 2023
bibkey: mishra2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11462"}
tags: ['Agentic', 'Applications', 'Training Techniques']
---
Generating high45;quality summaries for chat dialogs often requires large labeled datasets. We propose a method to efficiently use unlabeled data for extractive summarization of customer45;agent dialogs. In our method we frame summarization as a question45;answering problem and use state45;of45;the45;art large language models (LLMs) to generate pseudo45;labels for a dialog. We then use these pseudo45;labels to fine45;tune a chat summarization model effectively transferring knowledge from the large LLM into a smaller specialized model. We demonstrate our method on the tweetsumm dataset and show that using 1037; of the original labelled data set we can achieve 65.9/57.0/61.0 ROUGE45;1/45;2/45;L whereas the current state45;of45;the45;art trained on the entire training data set obtains 65.16/55.81/64.37 ROUGE45;1/45;2/45;L. In other words in the worst case (i.e. ROUGE45;L) we still effectively retain 94.737; of the performance while using only 1037; of the data.
