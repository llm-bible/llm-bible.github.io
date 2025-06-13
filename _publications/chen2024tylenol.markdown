---
layout: publication
title: 'Wait, But Tylenol Is Acetaminophen... Investigating And Improving Language Models'' Ability To Resist Requests For Misinformation'
authors: Shan Chen, Mingye Gao, Kuleen Sasse, Thomas Hartvigsen, Brian Anthony, Lizhou Fan, Hugo Aerts, Jack Gallifant, Danielle Bitterman
conference: "Arxiv"
year: 2024
bibkey: chen2024tylenol
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.20385"}
tags: ['Fine-Tuning', 'Security', 'Prompting']
---
Background: Large language models (LLMs) are trained to follow directions,
but this introduces a vulnerability to blindly comply with user requests even
if they generate wrong information. In medicine, this could accelerate the
generation of misinformation that impacts human well-being.
  Objectives/Methods: We analyzed compliance to requests to generate misleading
content about medications in settings where models know the request is
illogical. We investigated whether in-context directions and instruction-tuning
of LLMs to prioritize logical reasoning over compliance reduced misinformation
risk.
  Results: While all frontier LLMs complied with misinformation requests, both
prompt-based and parameter-based approaches can improve the detection of logic
flaws in requests and prevent the dissemination of medical misinformation.
  Conclusion: Shifting LLMs to prioritize logic over compliance could reduce
risks of exploitation for medical misinformation.
