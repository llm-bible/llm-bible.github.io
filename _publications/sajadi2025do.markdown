---
layout: publication
title: 'Do Llms Consider Security? An Empirical Study On Responses To Programming Questions'
authors: Amirali Sajadi, Binh Le, Anh Nguyen, Kostadin Damevski, Preetha Chatterjee
conference: "Arxiv"
year: 2025
bibkey: sajadi2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14202"}
tags: ['Responsible AI', 'GPT', 'Model Architecture', 'Security', 'Prompting']
---
The widespread adoption of conversational LLMs for software development has
raised new security concerns regarding the safety of LLM-generated content. Our
motivational study outlines ChatGPT's potential in volunteering
context-specific information to the developers, promoting safe coding
practices. Motivated by this finding, we conduct a study to evaluate the degree
of security awareness exhibited by three prominent LLMs: Claude 3, GPT-4, and
Llama 3. We prompt these LLMs with Stack Overflow questions that contain
vulnerable code to evaluate whether they merely provide answers to the
questions or if they also warn users about the insecure code, thereby
demonstrating a degree of security awareness. Further, we assess whether LLM
responses provide information about the causes, exploits, and the potential
fixes of the vulnerability, to help raise users' awareness. Our findings show
that all three models struggle to accurately detect and warn users about
vulnerabilities, achieving a detection rate of only 12.6% to 40% across our
datasets. We also observe that the LLMs tend to identify certain types of
vulnerabilities related to sensitive information exposure and improper input
neutralization much more frequently than other types, such as those involving
external control of file names or paths. Furthermore, when LLMs do issue
security warnings, they often provide more information on the causes, exploits,
and fixes of vulnerabilities compared to Stack Overflow responses. Finally, we
provide an in-depth discussion on the implications of our findings and present
a CLI-based prompting tool that can be used to generate significantly more
secure LLM responses.
