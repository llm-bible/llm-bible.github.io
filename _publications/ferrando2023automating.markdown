---
layout: publication
title: Automating Behavioral Testing in Machine Translation
authors: Ferrando Javier, Sperber Matthias, Setiawan Hendra, Telaar Dominic, Hasan Saša
conference: "Arxiv"
year: 2023
bibkey: ferrando2023automating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02553"}
tags: ['Applications', 'Tools']
---
Behavioral testing in NLP allows fine-grained evaluation of systems by examining their linguistic capabilities through the analysis of input-output behavior. Unfortunately existing work on behavioral testing in Machine Translation (MT) is currently restricted to largely handcrafted tests covering a limited range of capabilities and languages. To address this limitation we propose to use Large Language Models (LLMs) to generate a diverse set of source sentences tailored to test the behavior of MT models in a range of situations. We can then verify whether the MT model exhibits the expected behavior through matching candidate sets that are also generated using LLMs. Our approach aims to make behavioral testing of MT systems practical while requiring only minimal human effort. In our experiments we apply our proposed evaluation framework to assess multiple available MT systems revealing that while in general pass-rates follow the trends observable from traditional accuracy-based metrics our method was able to uncover several important differences and potential bugs that go unnoticed when relying only on accuracy.
