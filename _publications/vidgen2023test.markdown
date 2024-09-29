---
layout: publication
title: Simplesafetytests&#58; A Test Suite For Identifying Critical Safety Risks In Large Language Models
authors: Vidgen Bertie, Scherrer Nino, Kirk Hannah Rose, Qian Rebecca, Kannappan Anand, Hale Scott A., Röttger Paul
conference: "Arxiv"
year: 2023
bibkey: vidgen2023test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08370"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Tools']
---
The past year has seen rapid acceleration in the development of large language models (LLMs). However without proper steering and safeguards LLMs will readily follow malicious instructions provide unsafe advice and generate toxic content. We introduce SimpleSafetyTests (SST) as a new test suite for rapidly and systematically identifying such critical safety risks. The test suite comprises 100 test prompts across five harm areas that LLMs for the vast majority of applications should refuse to comply with. We test 11 open-access and open-source LLMs and four closed-source LLMs and find critical safety weaknesses. While some of the models do not give a single unsafe response most give unsafe responses to more than 2037; of the prompts with over 5037; unsafe responses in the extreme. Prepending a safety-emphasising system prompt substantially reduces the occurrence of unsafe responses but does not completely stop them from happening. Trained annotators labelled every model response to SST (n = 3000). We use these annotations to evaluate five AI safety filters (which assess whether a models response is unsafe given a prompt) as a way of automatically evaluating models performance on SST. The filters performance varies considerably. There are also differences across the five harm areas and on the unsafe versus safe responses. The widely-used Perspective API has 7237; accuracy and a newly-created zero-shot prompt to OpenAIs GPT-4 performs best with 8937; accuracy. Content Warning This paper contains prompts and responses that relate to child abuse suicide self-harm and eating disorders scams and fraud illegal items and physical harm.
