---
layout: publication
title: Towards More Trustworthy And Interpretable Llms For Code Through Syntax-grounded Explanations
authors: Palacio David N., Rodriguez-cardenas Daniel, Velasco Alejandro, Khati Dipin, Moran Kevin, Poshyvanyk Denys
conference: "Arxiv"
year: 2024
bibkey: palacio2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08983"}
tags: ['Interpretability And Explainability']
---
Trustworthiness and interpretability are inextricably linked concepts for LLMs. The more interpretable an LLM is the more trustworthy it becomes. However current techniques for interpreting LLMs when applied to code-related tasks largely focus on accuracy measurements measures of how models react to change or individual task performance instead of the fine-grained explanations needed at prediction time for greater interpretability and hence trust. To improve upon this status quo this paper introduces ASTrust an interpretability method for LLMs of code that generates explanations grounded in the relationship between model confidence and syntactic structures of programming languages. ASTrust explains generated code in the context of syntax categories based on Abstract Syntax Trees and aids practitioners in understanding model predictions at both local (individual code snippets) and global (larger datasets of code) levels. By distributing and assigning model confidence scores to well-known syntactic structures that exist within ASTs our approach moves beyond prior techniques that perform token-level confidence mapping by offering a view of model confidence that directly aligns with programming language concepts with which developers are familiar. To put ASTrust into practice we developed an automated visualization that illustrates the aggregated model confidence scores superimposed on sequence heat-map and graph-based visuals of syntactic structures from ASTs. We examine both the practical benefit that ASTrust can provide through a data science study on 12 popular LLMs on a curated set of GitHub repos and the usefulness of ASTrust through a human study.
