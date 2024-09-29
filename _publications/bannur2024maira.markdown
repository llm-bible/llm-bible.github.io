---
layout: publication
title: MAIRA-2&#58; Grounded Radiology Report Generation
authors: Bannur Shruthi, Bouzid Kenza, Castro Daniel C., Schwaighofer Anton, Bond-taylor Sam, Ilse Maximilian, Pérez-garcía Fernando, Salvatelli Valentina, Sharma Harshita, Meissen Felix, Ranjit Mercy, Srivastav Shaury, Gong Julia, Falck Fabian, Oktay Ozan, Thieme Anja, Lungren Matthew P., Wetscherek Maria Teodora, Alvarez-valle Javier, Hyland Stephanie L.
conference: "Arxiv"
year: 2024
bibkey: bannur2024maira
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04449"}
tags: ['Ethics And Bias', 'Multimodal Models', 'RAG', 'Tools']
---
Radiology reporting is a complex task that requires detailed image understanding integration of multiple inputs including comparison with prior imaging and precise language generation. This makes it ideal for the development and use of generative multimodal models. Here we extend report generation to include the localisation of individual findings on the image - a task we call grounded report generation. Prior work indicates that grounding is important for clarifying image understanding and interpreting AI-generated text. Therefore grounded reporting stands to improve the utility and transparency of automated report drafting. To enable evaluation of grounded reporting we propose a novel evaluation framework - RadFact - leveraging the reasoning capabilities of large language models (LLMs). RadFact assesses the factuality of individual generated sentences as well as correctness of generated spatial localisations when present. We introduce MAIRA-2 a large multimodal model combining a radiology-specific image encoder with a LLM and trained for the new task of grounded report generation on chest X-rays. MAIRA-2 uses more comprehensive inputs than explored previously the current frontal image the current lateral image the prior frontal image and prior report as well as the Indication Technique and Comparison sections of the current report. We demonstrate that these additions significantly improve report quality and reduce hallucinations establishing a new state of the art on findings generation (without grounding) on MIMIC-CXR while demonstrating the feasibility of grounded reporting as a novel and richer task.
