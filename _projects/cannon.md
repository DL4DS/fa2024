---
authors: ["Jessica Cannon"]
title: Sudan Agricultural Advising Consultant
paper_url: /static_files/projects/cannon_agri_advisor.pdf
video_url: "https://mymedia.bu.edu/media/t/1_lj0e6hnr"
slides_url: /static_files/projects/cannon_preso.pdf
tags: ["LLM", "RAG", "RAG Evaluation"]
---

This project report describes the development of a question-and-answer (Q&A)
chatbot, empowered by deep learning-based Language Model technology, to address
the challenges faced by Sudanese farmers. I adapted and fine-tuned the existing GPT-
4 LLM to the Sudanese agricultural context via RAG implementation, leveraging four
large publicly available datasets from reputable sources. Evaluation of the chatbot’s
performance was conducted using the TruLens evaluation functions for Groundedness,
Context Relevance and Answer Relevance [3], as well as a qualitative comparison of the
RAG model’s responses against the original model’s responses to relevant queries. The
results showed that the RAG model did well in both Context and Answer Relevance,
as well as being domain specific and versatile within the domain. It also had a higher
accuracy compared to the baseline when compared to ground truth data. However,
the RAG model struggled with Groundedness and was less detailed with advice than
the baseline model, which is most likely attributed to the source datasets not including
enough specific contextual detail. Future work will ideally focus on further refining the
LLM’s capabilities and evaluating its long-term impact on agricultural productivity
and livelihoods in Sudan.
