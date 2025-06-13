---
layout: publication
title: 'Capability-driven Skill Generation With Llms: A Rag-based Approach For Reusing Existing Libraries And Interfaces'
authors: Luis Miguel Vieira Da Silva, Aljosha Köcher, Nicolas König, Felix Gehlhoff, Alexander Fay
conference: "Arxiv"
year: 2025
bibkey: dasilva2025capability
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03295'}
tags: ['RAG', 'Model Architecture', 'Applications', 'Tools']
---
Modern automation systems increasingly rely on modular architectures, with
capabilities and skills as one solution approach. Capabilities define the
functions of resources in a machine-readable form and skills provide the
concrete implementations that realize those capabilities. However, the
development of a skill implementation conforming to a corresponding capability
remains a time-consuming and challenging task. In this paper, we present a
method that treats capabilities as contracts for skill implementations and
leverages large language models to generate executable code based on natural
language user input. A key feature of our approach is the integration of
existing software libraries and interface technologies, enabling the generation
of skill implementations across different target languages. We introduce a
framework that allows users to incorporate their own libraries and resource
interfaces into the code generation process through a retrieval-augmented
generation architecture. The proposed method is evaluated using an autonomous
mobile robot controlled via Python and ROS 2, demonstrating the feasibility and
flexibility of the approach.
