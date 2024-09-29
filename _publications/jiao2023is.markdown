---
layout: publication
title: Is Chatgpt A Good Translator Yes With GPT45;4 As The Engine
authors: Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Xing Wang, Shuming Shi, Zhaopeng Tu
conference: "Arxiv"
year: 2023
bibkey: jiao2023is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2301.08745v4"}
  - {name: "Code", url: "https://github.com/wxjiao/Is&#45;ChatGPT&#45;A&#45;Good&#45;Translator"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Security']
---
This report provides a preliminary evaluation of ChatGPT for machine translation including translation prompt multilingual translation and translation robustness. We adopt the prompts advised by ChatGPT to trigger its translation ability and find that the candidate prompts generally work well with minor performance differences. By evaluating on a number of benchmark test sets we find that ChatGPT performs competitively with commercial translation products (e.g. Google Translate) on high45;resource European languages but lags behind significantly on low45;resource or distant languages. As for the translation robustness ChatGPT does not perform as well as the commercial systems on biomedical abstracts or Reddit comments but exhibits good results on spoken language. Further we explore an interesting strategy named mathbf123;pivot~prompting125; for distant languages which asks ChatGPT to translate the source sentence into a high45;resource pivot language before into the target language improving the translation performance noticeably. With the launch of the GPT45;4 engine the translation performance of ChatGPT is significantly boosted becoming comparable to commercial translation products even for distant languages. Human analysis on Google Translate and ChatGPT suggests that ChatGPT with GPT45;3.5 tends to generate more hallucinations and mis45;translation errors while that with GPT45;4 makes the least errors. In other words ChatGPT has already become a good translator. Please refer to our Github project for more details https://github.com/wxjiao/Is&#45;ChatGPT&#45;A&#45;Good&#45;Translator
