---
layout: publication
title: 'Extracting Memorized Training Data Via Decomposition'
authors: Ellen Su, Anu Vellore, Amy Chang, Raffaele Mura, Blaine Nelson, Paul Kassianik, Amin Karbasi
conference: "Arxiv"
year: 2024
bibkey: su2024extracting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12367"}
tags: ['Responsible AI', 'RAG', 'Training Techniques', 'Security']
---
The widespread use of Large Language Models (LLMs) in society creates new
information security challenges for developers, organizations, and end-users
alike. LLMs are trained on large volumes of data, and their susceptibility to
reveal the exact contents of the source training datasets poses security and
safety risks. Although current alignment procedures restrict common risky
behaviors, they do not completely prevent LLMs from leaking data. Prior work
demonstrated that LLMs may be tricked into divulging training data by using
out-of-distribution queries or adversarial techniques. In this paper, we
demonstrate a simple, query-based decompositional method to extract news
articles from two frontier LLMs. We use instruction decomposition techniques to
incrementally extract fragments of training data. Out of 3723 New York Times
articles, we extract at least one verbatim sentence from 73 articles, and over
20% of verbatim sentences from 6 articles. Our analysis demonstrates that this
method successfully induces the LLM to generate texts that are reliable
reproductions of news articles, meaning that they likely originate from the
source training dataset. This method is simple, generalizable, and does not
fine-tune or change the production model. If replicable at scale, this training
data extraction methodology could expose new LLM security and safety
vulnerabilities, including privacy risks and unauthorized data leaks. These
implications require careful consideration from model development to its
end-use.
