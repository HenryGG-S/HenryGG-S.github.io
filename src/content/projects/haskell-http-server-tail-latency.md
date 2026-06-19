---
title: "Haskell HTTP/1.1 Server — Tail Latency Study"
description: "A dissertation project implementing a lean HTTP/1.1 server in Haskell to investigate runtime behaviour and tail latency under load."
date: 2026-05-01
tags: ["haskell", "http", "performance", "benchmarking", "runtime-profiling", "systems"]
repo: "https://github.com/HenryGG-S/Year-4-Individual-Project"
draft: false
featured: true
---

For my MSci dissertation, I implemented a lean, standards-aware HTTP/1.1 server in Haskell to support controlled benchmarking and performance investigation.

The project focused on tail latency, particularly p95 to p99.9 response times under open-loop load. I investigated how runtime scheduling and garbage collection behaviour affected worst-case response times, using GHC runtime-system statistics and established Haskell web servers as reference points for comparison.

The main value of the project was not simply building a web server, but creating a reproducible experimental baseline and reasoning carefully about the relationship between implementation choices, runtime behaviour, and observed system performance.
