---
layout: publication
title: 'Beyond Accuracy: The Role Of Calibration In Self-improving Large Language Models'
authors: Liangjie Huang, Dawei Li, Huan Liu, Lu Cheng
conference: "Arxiv"
year: 2025
bibkey: huang2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02902"}
tags: ['Prompting', 'Ethics and Bias']
---
Large Language Models (LLMs) have demonstrated remarkable self-improvement
capabilities, whereby models iteratively revise their outputs through
self-generated feedback. While this reflective mechanism has shown promise in
enhancing task performance, recent studies suggest that it may also introduce
undesirable biases-most notably, self-bias, or the tendency of LLMs to favor
their own prior outputs. In this work, we extend this line of inquiry by
investigating the impact on confidence estimation. We evaluate three
representative self-improvement paradigms-basic prompting, Chain-of-Thought
(CoT) prompting, and tuning-based methods and find that iterative
self-improvement can lead to systematic overconfidence, as evidenced by a
steadily increasing Expected Calibration Error (ECE) and lower accuracy with
high confidence. We then further explore the integration of confidence
calibration techniques with self-improvement. Specifically, we compare three
strategies: (1) applying calibration after multiple rounds of self-improvement,
(2) calibrating before self-improvement, and (3) applying calibration
iteratively at each self-improvement step. Our results show that iterative
calibration is most effective in reducing ECE, yielding improved calibration.
Our work pioneers the study of self-improving LLMs from a calibration
perspective, offering valuable insights into balancing model performance and
reliability.
