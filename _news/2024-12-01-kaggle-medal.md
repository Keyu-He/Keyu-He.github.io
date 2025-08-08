---
layout: post
title: Silver Medal in Kaggle Competition
date: 2024-06-21
---

Thrilled to share that our team won a **silver medal** (**top 3.4% globally**) in the LLM-Prompt-Recovery Challenge on Kaggle! 🥈

The task involved recovering original user prompts from Gemma-generated completions. I led model finetuning focusing on a custom scoring strategy: a sharpened cosine similarity using sentence-t5-base.

We used LoRA for efficient finetuning, and also explored light adversarial attacks, such as appending generic prompts, to game the metric. We ultimately achieving a high similarity score of 0.657, only 0.059 away from the top team.

A fun and rewarding challenge blending research and engineering!
