---
title: "DeepSeek R1 笔记"
cover: "feature.png"
date: 2025-02-03
lastmod: 2025-02-03
draft: false
description: "文献笔记：DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning"
slug: "deepseek r1"
tags: ["LLM", "RL", "survey"]
showDateUpdated: true
math: true
---

对于 LLM 以及对应的 RL，我还是很陌生的。借着这个机会写点笔记学习一下。

## Pipeline

先整理一下 R1 的整个 Pipeline。整个 R1 报告发布了三组模型：1）DeepSeek-R1-Zero；2）DeepSeek-R1；3）DeepSeek-R1-Distill。三者的训练 Pipeline 如下所示：

![deepseek-r1 pipeline](./assets/d1_00.png)

其中，用于 R1 本体以及后续蒸馏模型的 “Combined SFT Data” 的构建 Pipeline 如下：

![deepseek-r1 data pipeline](./assets/d2_00.png)
