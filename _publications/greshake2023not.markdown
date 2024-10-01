---
layout: publication
title: 'Not What You''ve Signed Up For: Compromising Real-world Llm-integrated Applications With Indirect Prompt Injection'
authors: Greshake Kai, Abdelnabi Sahar, Mishra Shailesh, Endres Christoph, Holz Thorsten, Fritz Mario
conference: "Arxiv"
year: 2023
bibkey: greshake2023not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.12173"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Merging', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Tools']
---
Large Language Models (LLMs) are increasingly being integrated into various applications. The functionalities of recent LLMs can be flexibly modulated via natural language prompts. This renders them susceptible to targeted adversarial prompting, e.g., Prompt Injection (PI) attacks enable attackers to override original instructions and employed controls. So far, it was assumed that the user is directly prompting the LLM. But, what if it is not the user prompting? We argue that LLM-Integrated Applications blur the line between data and instructions. We reveal new attack vectors, using Indirect Prompt Injection, that enable adversaries to remotely (without a direct interface) exploit LLM-integrated applications by strategically injecting prompts into data likely to be retrieved. We derive a comprehensive taxonomy from a computer security perspective to systematically investigate impacts and vulnerabilities, including data theft, worming, information ecosystem contamination, and other novel security risks. We demonstrate our attacks' practical viability against both real-world systems, such as Bing's GPT-4 powered Chat and code-completion engines, and synthetic applications built on GPT-4. We show how processing retrieved prompts can act as arbitrary code execution, manipulate the application's functionality, and control how and if other APIs are called. Despite the increasing integration and reliance on LLMs, effective mitigations of these emerging threats are currently lacking. By raising awareness of these vulnerabilities and providing key insights into their implications, we aim to promote the safe and responsible deployment of these powerful models and the development of robust defenses that protect users and systems from potential attacks.
