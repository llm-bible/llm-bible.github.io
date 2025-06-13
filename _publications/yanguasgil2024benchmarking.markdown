---
layout: publication
title: 'Benchmarking Large Language Models For Materials Synthesis: The Case Of Atomic Layer Deposition'
authors: Angel Yanguas-gil, Matthew T. Dearing, Jeffrey W. Elam, Jessica C. Jones, Sungjoon Kim, Adnan Mohammad, Chi Thang Nguyen, Bratin Sengupta
conference: "Arxiv"
year: 2024
bibkey: yanguasgil2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10477"}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture']
---
In this work we introduce an open-ended question benchmark, ALDbench, to
evaluate the performance of large language models (LLMs) in materials
synthesis, and in particular in the field of atomic layer deposition, a thin
film growth technique used in energy applications and microelectronics. Our
benchmark comprises questions with a level of difficulty ranging from graduate
level to domain expert current with the state of the art in the field. Human
experts reviewed the questions along the criteria of difficulty and
specificity, and the model responses along four different criteria: overall
quality, specificity, relevance, and accuracy. We ran this benchmark on an
instance of OpenAI's GPT-4o. The responses from the model received a composite
quality score of 3.7 on a 1 to 5 scale, consistent with a passing grade.
However, 36% of the questions received at least one below average score. An
in-depth analysis of the responses identified at least five instances of
suspected hallucination. Finally, we observed statistically significant
correlations between the difficulty of the question and the quality of the
response, the difficulty of the question and the relevance of the response, and
the specificity of the question and the accuracy of the response as graded by
the human experts. This emphasizes the need to evaluate LLMs across multiple
criteria beyond difficulty or accuracy.
