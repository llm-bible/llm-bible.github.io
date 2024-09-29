---
layout: publication
title: Medinsight\: A Multi-source Context Augmentation Framework For Generating Patient-centric Medical Responses Using Large Language Models
authors: Neupane Subash, Mitra Shaswata, Mittal Sudip, Golilarz Noorbakhsh Amiri, Rahimi Shahram, Amirlatifi Amin
conference: "Arxiv"
year: 2024
bibkey: neupane2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08607"}
tags: ['Applications', 'Prompting', 'RAG', 'Tools']
---
Large Language Models (LLMs) have shown impressive capabilities in generating human-like responses. However their lack of domain-specific knowledge limits their applicability in healthcare settings where contextual and comprehensive responses are vital. To address this challenge and enable the generation of patient-centric responses that are contextually relevant and comprehensive we propose MedInsighta novel retrieval augmented framework that augments LLM inputs (prompts) with relevant background information from multiple sources. MedInsight extracts pertinent details from the patients medical record or consultation transcript. It then integrates information from authoritative medical textbooks and curated web resources based on the patients health history and condition. By constructing an augmented context combining the patients record with relevant medical knowledge MedInsight generates enriched patient-specific responses tailored for healthcare applications such as diagnosis treatment recommendations or patient education. Experiments on the MTSamples dataset validate MedInsights effectiveness in generating contextually appropriate medical responses. Quantitative evaluation using the Ragas metric and TruLens for answer similarity and answer correctness demonstrates the models efficacy. Furthermore human evaluation studies involving Subject Matter Expert (SMEs) confirm MedInsights utility with moderate inter-rater agreement on the relevance and correctness of the generated responses.
