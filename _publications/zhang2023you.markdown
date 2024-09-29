---
layout: publication
title: You Only Look At Screens Multimodal Chain45;of45;action Agents
authors: Zhang Zhuosheng, Zhang Aston
conference: "Arxiv"
year: 2023
bibkey: zhang2023you
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11436"}
  - {name: "Code", url: "https://github.com/cooelf/Auto&#45;GUI"}
tags: ['Agentic', 'Efficiency And Optimization', 'Has Code', 'Multimodal Models', 'RAG', 'Tools']
---
Autonomous graphical user interface (GUI) agents aim to facilitate task automation by interacting with the user interface without manual intervention. Recent studies have investigated eliciting the capabilities of large language models (LLMs) for effective engagement in diverse environments. To align with the input45;output requirement of LLMs most existing approaches are developed under a sandbox setting where they rely on external tools and application45;specific APIs to parse the environment into textual elements and interpret the predicted actions. Consequently those approaches often grapple with inference inefficiency and error propagation risks. To mitigate the challenges we introduce Auto45;GUI a multimodal solution that directly interacts with the interface bypassing the need for environment parsing or reliance on application45;dependent APIs. Moreover we propose a chain45;of45;action technique 45;45; leveraging a series of intermediate previous action histories and future action plans 45;45; to help the agent decide what action to execute. We evaluate our approach on a new device45;control benchmark AITW with 30K unique instructions spanning multi45;step tasks such as application operation web searching and web shopping. Experimental results show that Auto45;GUI achieves state45;of45;the45;art performance with an action type prediction accuracy of 9037; and an overall action success rate of 7437;. Code is publicly available at https://github.com/cooelf/Auto&#45;GUI.
