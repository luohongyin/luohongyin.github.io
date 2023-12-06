---
layout: post
title: Hosted the Efficient & Robust language modeling seminar
date: 2022-10-05 16:11:00-0400
inline: false
---

We invited Hunter Lang from the MIT ClinicalNLP lab to give a talk on co-training language models.

***

On Wednesday Oct 12 (today!), Hunter Lang from MIT ClinicalML group will present his recent work on efficient learning of large language models at the SLS group meeting (open to all).
 
Title: Co-training improves prompt-based learning for large language models
Time: 2pm to 3pm, Oct 12
 
Location: 32-G882 (Hewlett Room)
Zoom: https://mit.zoom.us/j/96475577718
 
Abstract: We demonstrate that co-training (Blum & Mitchell, 1998) can improve the performance of prompt-based learning by using unlabeled data. While prompting has emerged as a promising paradigm for few-shot and zero-shot learning, it is often brittle and requires much larger models compared to the standard supervised setup. We find that co-training makes it possible to improve the original prompt model and at the same time learn a smaller, downstream task-specific model. In the case where we only have partial access to a prompt model (e.g., output probabilities from GPT-3 (Brown et al., 2020)) we learn a calibration model over the prompt outputs. When we have full access to the prompt model's gradients but full finetuning remains prohibitively expensive (e.g., T0 (Sanh et al., 2021)), we learn a set of soft prompt continuous vectors to iteratively update the prompt model. We find that models trained in this manner can significantly improve performance on challenging datasets where there is currently a large gap between prompt-based learning and fully-supervised models.
 
Latest studies following this work will also be discussed.
 
Bio: Hunter Lang is a Ph.D. student at MIT in the ClinicalML group advised by David Sontag. He is currently working on self-supervised learning, learning from weak supervision, and applications of these techniques to clinical machine learning. Previously, he was an AI Resident at Microsoft Research AI in Redmond, where he worked primarily on stochastic optimization. Before that, he finished my M.Eng. at MIT with David Sontag, where he worked on approximate inference in graphical models with Aravindan Vijayaraghavan.
 
 