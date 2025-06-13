---
layout: publication
title: 'Can Large Language Models Replicate ITS Feedback On Open-ended Math Questions?'
authors: Hunter Mcnichols, Jaewook Lee, Stephen Fancsali, Steve Ritter, Andrew Lan
conference: "Arxiv"
year: 2024
bibkey: mcnichols2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.06414'}
tags: ['Training Techniques']
---
Intelligent Tutoring Systems (ITSs) often contain an automated feedback
component, which provides a predefined feedback message to students when they
detect a predefined error. To such a feedback component, we often resort to
template-based approaches. These approaches require significant effort from
human experts to detect a limited number of possible student errors and provide
corresponding feedback. This limitation is exemplified in open-ended math
questions, where there can be a large number of different incorrect errors. In
our work, we examine the capabilities of large language models (LLMs) to
generate feedback for open-ended math questions, similar to that of an
established ITS that uses a template-based approach. We fine-tune both
open-source and proprietary LLMs on real student responses and corresponding
ITS-provided feedback. We measure the quality of the generated feedback using
text similarity metrics. We find that open-source and proprietary models both
show promise in replicating the feedback they see during training, but do not
generalize well to previously unseen student errors. These results suggest that
despite being able to learn the formatting of feedback, LLMs are not able to
fully understand mathematical errors made by students.
