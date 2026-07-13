---
title: "How to Compute GPU Capacity for GPT Models (GPT‑4o and Later)"
url: "https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/how-to-compute-gpu-capacity-for-gpt-models-gpt-4o-and-later/ba-p/4506930"
date: "2026-03-30"
author: "Yan_Liang"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=HealthcareAndLifeSciencesBlog"
---
When deploying large language models like GPT‑4o , capacity planning is no longer about picking a GPU SKU. Instead, Azure abstracts GPU compute behind Provisioned Throughput Units (PTUs) —a model‑centric way to reason about GPU usage, throughput, and latency. This post explains how GPU capacity is computed for GPT‑4o‑class models , and how to translate your workload into the right number of PTUs.
