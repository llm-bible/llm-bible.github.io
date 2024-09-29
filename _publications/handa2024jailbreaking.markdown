---
layout: publication
title: Jailbreaking Proprietary Large Language Models Using Word Substitution Cipher
authors: Handa Divij, Chirmule Advait, Gajera Bimal, Baral Chitta
conference: "Arxiv"
year: 2024
bibkey: handa2024jailbreaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10601"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Security']
---
Large Language Models (LLMs) are aligned to moral and ethical guidelines but remain susceptible to creative prompts called Jailbreak that can bypass the alignment process. However most jailbreaking prompts contain harmful questions in the natural language (mainly English) which can be detected by the LLM themselves. In this paper we present jailbreaking prompts encoded using cryptographic techniques. We first present a pilot study on the state45;of45;the45;art LLM GPT45;4 in decoding several safe sentences that have been encrypted using various cryptographic techniques and find that a straightforward word substitution cipher can be decoded most effectively. Motivated by this result we use this encoding technique for writing jailbreaking prompts. We present a mapping of unsafe words with safe words and ask the unsafe question using these mapped words. Experimental results show an attack success rate (up to 59.4237;) of our proposed jailbreaking approach on state45;of45;the45;art proprietary models including ChatGPT GPT45;4 and Gemini45;Pro. Additionally we discuss the over45;defensiveness of these models. We believe that our work will encourage further research in making these LLMs more robust while maintaining their decoding capabilities.
