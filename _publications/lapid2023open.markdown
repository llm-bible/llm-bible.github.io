---
layout: publication
title: Open Sesame! Universal Black Box Jailbreaking of Large Language Models
authors: Lapid Raz, Langberg Ron, Sipper Moshe
conference: "ICLR"
year: 2023
bibkey: lapid2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.01446"}
tags: ['Ethics And Bias', 'Model Architecture', 'Prompting', 'Responsible AI', 'Security']
---
Large language models (LLMs) designed to provide helpful and safe responses often rely on alignment techniques to align with user intent and social guidelines. Unfortunately this alignment can be exploited by malicious actors seeking to manipulate an LLMs outputs for unintended purposes. In this paper we introduce a novel approach that employs a genetic algorithm (GA) to manipulate LLMs when model architecture and parameters are inaccessible. The GA attack works by optimizing a universal adversarial prompt that -- when combined with a users query -- disrupts the attacked models alignment resulting in unintended and potentially harmful outputs. Our novel approach systematically reveals a models limitations and vulnerabilities by uncovering instances where its responses deviate from expected behavior. Through extensive experiments we demonstrate the efficacy of our technique thus contributing to the ongoing discussion on responsible AI development by providing a diagnostic tool for evaluating and enhancing alignment of LLMs with human intent. To our knowledge this is the first automated universal black box jailbreak attack.
