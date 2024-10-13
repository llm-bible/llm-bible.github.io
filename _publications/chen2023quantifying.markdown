---
layout: publication
title: 'Quantifying Uncertainty In Answers From Any Language Model And Enhancing Their Trustworthiness'
authors: Chen Jiuhai, Mueller Jonas
conference: "Arxiv"
year: 2023
bibkey: chen2023quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.16175"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Tools', 'Training Techniques', 'Uncategorized']
---
We introduce BSDetector, a method for detecting bad and speculative answers
from a pretrained Large Language Model by estimating a numeric confidence score
for any output it generated. Our uncertainty quantification technique works for
any LLM accessible only via a black-box API, whose training data remains
unknown. By expending a bit of extra computation, users of any LLM API can now
get the same response as they would ordinarily, as well as a confidence
estimate that cautions when not to trust this response. Experiments on both
closed and open-form Question-Answer benchmarks reveal that BSDetector more
accurately identifies incorrect LLM responses than alternative uncertainty
estimation procedures (for both GPT-3 and ChatGPT). By sampling multiple
responses from the LLM and considering the one with the highest confidence
score, we can additionally obtain more accurate responses from the same LLM,
without any extra training steps. In applications involving automated
evaluation with LLMs, accounting for our confidence scores leads to more
reliable evaluation in both human-in-the-loop and fully-automated settings
(across both GPT 3.5 and 4).
