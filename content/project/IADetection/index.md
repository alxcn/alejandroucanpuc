---
title: "Detection of LLM-generated text in Academic Scenarios"
subtitle: "A TDA viewpoint"
excerpt: "Use topological features to optimize the detection of LLM-generated text in academic scenarios."
date: 2025-01-29
author: "Alejandro Ucan-Puc"
draft: false
tags:
  - research
  - TDA
  - IA
categories:
  - research
  - TDA
  - IA
layout: single
links:
- icon: github
  icon_pack: fab
  name: code
  url: 
---

With the exploding use of LLM Neural Networks, it is common to encounter IA generated text in different scenarios: news, images, papers, etc. This propose a new ethic problem in academic scenarios: how to identify the use of LLM-generated text in student's submissions?

There are some work and software that intent to solve that problem, for example:

* _HowkGPT: Investigating the Detection of ChatGPT-generated University Student Homework through Context-Aware Perplexity Analysis_. Christoforos Vasilatos, Manaar Alam, Talal Rahwan, Yasir Zaki, Michail Maniatakos. __ArXiv__ (https://arxiv.org/abs/2305.18226) 

 

* _ChatGPT in Undergraduate Education: Performance of GPT-3.5 and Identification of AI-Generated Text in Introductory Neuroscience_. Natalie V. Covington & Olivia Vruwink. __International Journal of Artificial Intelligence in Education__ (https://link.springer.com/article/10.1007/s40593-024-00427-9) 

 

* _ConDA: Contrastive Domain Adaptation for AI-generated Text Detection_. Amrita Bhattacharjee, Tharindu Kumarage, Raha Moraffah, Huan Liu. __ArXiv__ (https://arxiv.org/abs/2309.03992)

 

* _Evaluating the efficacy of AI content detection tools in differentiating between human and AI-generated text_. Ahmed M. Elkhatat, Khaled Elsaid & Saeed Almeer. __International Journal for Educational Integrity__ (https://link.springer.com/article/10.1007/s40979-023-00140-5)

Nevertheless, those software rely on a large data set and nowadays it is almost imposible to maintain a curated database without the presence of IA-generated text.

In Deng and Duzhin (2022)![https://www.mdpi.com/2504-2289/6/3/74], the authors provide a way to clasify fakenews using Neural networks and topology with a small data set, with a hig accury and performance.

Our project is to replicate that paper in an academic scenario with curated and small databases, and implement those Neural Networks in an adaptable software.

This project started in December July 2024, as a proposition of  Ángel Azahel Ramirez (a01383328@tec.mx, MTY), and have been actively studied in collaboration of:

1. Luis Roberto Garza Sanchez (a00836982@tec.mx, MTY)
2. Erick Isaac Lascano Otañez (a00836571@tec.mx, MTY)
3. Juan Pablo Bernal Lafarga (a01742342@tec.mx, MTY)
4. Lilia Alanís-López (lilia.alanislpz@tec.mx, MTY)

Our first results with a 0.9 accuracy using a answer-response database. We are working actively on the paper with the proper results.

Some concepts and algorithm used in this prjects are:

* Persistent homology.
* Persistent Images.
* LSTM Neural Network.
* BERT Neural Network.
* GloVe algorithm.
* LLMs.
