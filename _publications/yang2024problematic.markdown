---
layout: publication
title: 'Problematic Tokens: Tokenizer Bias In Large Language Models'
authors: Jin Yang, Zhiqiang Wang, Yanbin Lin, Zunduo Zhao
conference: "Arxiv"
year: 2024
bibkey: yang2024problematic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.11214'}
  - {name: "Code", url: 'https://github.com/yeyimilk/LLMGPT4o'}
tags: ['Has Code', 'Security', 'GPT', 'Model Architecture', 'Training Techniques', 'Tools', 'Ethics and Bias', 'Tokenization']
---
Recent advancements in large language models(LLMs), such as GPT-4 and GPT-4o,
have shown exceptional performance, especially in languages with abundant
resources like English, thanks to extensive datasets that ensure robust
training. Conversely, these models exhibit limitations when processing
under-resourced languages such as Chinese and Korean, where issues including
hallucinatory responses remain prevalent. This paper traces the roots of these
disparities to the tokenization process inherent to these models. Specifically,
it explores how the tokenizers vocabulary, often used to speed up the
tokenization process and reduce tokens but constructed independently of the
actual model training data, inadequately represents non-English languages. This
misrepresentation results in the propagation of under-trained or untrained
tokens, which perpetuate biases and pose serious concerns related to data
security and ethical standards. We aim to dissect the tokenization mechanics of
GPT-4o, illustrating how its simplified token-handling methods amplify these
risks and offer strategic solutions to mitigate associated security and ethical
issues. Through this study, we emphasize the critical need to rethink
tokenization frameworks to foster more equitable and secure AI technologies.
The code and data are available at https://github.com/yeyimilk/LLMGPT4o
