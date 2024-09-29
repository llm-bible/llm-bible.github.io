---
layout: publication
title: Satyrn A Platform for Analytics Augmented Generation
authors: Sterbentz Marko, Barrie Cameron, Shahi Shubham, Dutta Abhratanu, Hooshmand Donna, Pack Harper, Hammond Kristian J.
conference: "Arxiv"
year: 2024
bibkey: sterbentz2024satyrn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12069"}
tags: ['GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) are capable of producing documents and retrieval augmented generation (RAG) has shown itself to be a powerful method for improving accuracy without sacrificing fluency. However not all information can be retrieved from text. We propose an approach that uses the analysis of structured data to generate fact sets that are used to guide generation in much the same way that retrieved documents are used in RAG. This analytics augmented generation (AAG) approach supports the ability to utilize standard analytic techniques to generate facts that are then converted to text and passed to an LLM. We present a neurosymbolic platform Satyrn that leverages AAG to produce accurate fluent and coherent reports grounded in large scale databases. In our experiments we find that Satyrn generates reports in which over 86 accurate claims while maintaining high levels of fluency and coherence even when using smaller language models such as Mistral-7B as compared to GPT-4 Code Interpreter in which just 57 of claims are accurate.
