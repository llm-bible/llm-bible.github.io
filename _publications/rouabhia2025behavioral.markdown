---
layout: publication
title: 'Behavioral Augmentation Of UML Class Diagrams: An Empirical Study Of Large Language Models For Method Generation'
authors: Djaber Rouabhia, Ismail Hadjadj
conference: "Arxiv"
year: 2025
bibkey: rouabhia2025behavioral
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00788"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Automating the enrichment of UML class diagrams with behavioral methods from natural language use cases is a significant challenge. This study evaluates nine large language models (LLMs) in augmenting a methodless UML diagram (21 classes, 17 relationships) using 21 structured waste-management use cases. A total of 90 diagrams (3,373 methods) were assessed across six metrics: method quantity, signature richness (visibility, names, parameters, return types), annotation completeness (linking to use cases/actions), structural fidelity, syntactic correctness (PlantUML compilation), and naming convergence (across models). All LLMs produced valid PlantUML diagrams adhering to UML conventions. Some models excelled in method coverage and annotation accuracy, while others showed richer parameterization but weaker traceability. These results demonstrate that LLMs can generate well-structured methods with consistent naming, advancing automated behavioral modeling. However, inconsistencies in annotations and signatures highlight the need for improved prompt engineering and model selection. The rapid generation of these methods supports Agile practices by enabling faster design iterations. Despite their capabilities, human oversight is essential to ensure accuracy, appropriateness, and semantic alignment. This positions LLMs as collaborative partners in software design. All experimental artifacts (\texttt\{.puml\}, \texttt\{.png\}, \texttt\{.csv\}) are publicly available for reproducibility.
