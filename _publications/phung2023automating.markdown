---
layout: publication
title: Automating Human Tutor45;style Programming Feedback Leveraging GPT45;4 Tutor Model For Hint Generation And GPT45;3.5 Student Model For Hint Validation
authors: Phung Tung, Pădurean Victor-alexandru, Singh Anjali, Brooks Christopher, Cambronero José, Gulwani Sumit, Singla Adish, Soares Gustavo
conference: "Arxiv"
year: 2023
bibkey: phung2023automating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03780"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Generative AI and large language models hold great promise in enhancing programming education by automatically generating individualized feedback for students. We investigate the role of generative AI models in providing human tutor45;style programming hints to help students resolve errors in their buggy programs. Recent works have benchmarked state45;of45;the45;art models for various feedback generation scenarios; however their overall quality is still inferior to human tutors and not yet ready for real45;world deployment. In this paper we seek to push the limits of generative AI models toward providing high45;quality programming hints and develop a novel technique GPT4Hints45;GPT3.5Val. As a first step our technique leverages GPT45;4 as a tutor model to generate hints 45;45; it boosts the generative quality by using symbolic information of failing test cases and fixes in prompts. As a next step our technique leverages GPT45;3.5 a weaker model as a student model to further validate the hint quality 45;45; it performs an automatic quality validation by simulating the potential utility of providing this feedback. We show the efficacy of our technique via extensive evaluation using three real45;world datasets of Python programs covering a variety of concepts ranging from basic algorithms to regular expressions and data analysis using pandas library.
