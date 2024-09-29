---
layout: publication
title: On The Impacts Of Contexts On Repository-level Code Generation
authors: Hai Nam Le, Nguyen Dung Manh, Bui Nghi D. Q.
conference: "Arxiv"
year: 2024
bibkey: hai2024impacts
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11927"}
  - {name: "Code", url: "https://github.com/FSoft-AI4Code/RepoExec"}
tags: ['Applications', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools']
---
CodeLLMs have gained widespread adoption for code generation tasks yet their capacity to handle repository-level code generation with complex contextual dependencies remains underexplored. Our work underscores the critical importance of leveraging repository-level contexts to generate executable and functionally correct code. We present a novel benchmark designed to evaluate repository-level code generation with a focus on three key aspects executability functional correctness through comprehensive test case generation and accurate utilization of cross-file contexts. Our study examines a controlled scenario where developers specify essential code dependencies (contexts) challenging models to integrate them effectively. Additionally we introduce an instruction-tuned dataset that enhances CodeLLMs ability to leverage dependencies along with a new metric to quantify context utilization. Experimental results reveal that while pretrained LLMs demonstrate superior performance in terms of correctness instruction-tuned models excel in context utilization and debugging capabilities. methodnamews offers a comprehensive evaluation framework for assessing code functionality and alignment with developer intent thereby advancing the development of more reliable CodeLLMs for real-world applications. The dataset and source code are available at~urlhttps://github.com/FSoft-AI4Code/RepoExec}.
