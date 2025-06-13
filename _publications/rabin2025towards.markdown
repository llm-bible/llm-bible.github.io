---
layout: publication
title: 'Sandboxeval: Towards Securing Test Environment For Untrusted Code'
authors: Rafiqul Rabin, Jesse Hostetler, Sean Mcgregor, Brett Weir, Nick Judd
conference: "Arxiv"
year: 2025
bibkey: rabin2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00018"}
tags: ['Responsible AI', 'Security', 'Tools', 'Reinforcement Learning']
---
While large language models (LLMs) are powerful assistants in programming
tasks, they may also produce malicious code. Testing LLM-generated code
therefore poses significant risks to assessment infrastructure tasked with
executing untrusted code. To address these risks, this work focuses on
evaluating the security and confidentiality properties of test environments,
reducing the risk that LLM-generated code may compromise the assessment
infrastructure. We introduce SandboxEval, a test suite featuring manually
crafted test cases that simulate real-world safety scenarios for LLM assessment
environments in the context of untrusted code execution. The suite evaluates
vulnerabilities to sensitive information exposure, filesystem manipulation,
external communication, and other potentially dangerous operations in the
course of assessment activity. We demonstrate the utility of SandboxEval by
deploying it on an open-source implementation of Dyff, an established AI
assessment framework used to evaluate the safety of LLMs at scale. We show,
first, that the test suite accurately describes limitations placed on an LLM
operating under instructions to generate malicious code. Second, we show that
the test results provide valuable insights for developers seeking to harden
assessment infrastructure and identify risks associated with LLM execution
activities.
