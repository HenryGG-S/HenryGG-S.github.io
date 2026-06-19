---
title: "Satcom NMS Toy"
description: "A design-stage ground-segment toy system exploring telemetry ingest, strict protocol parsing, alarms, command scheduling, and audit trails."
date: 2026-06-01
tags: ["ground-segment", "telemetry", "protocols", "systems-design", "space-software"]
repo: "https://github.com/HenryGG-S/satcom-nms-toy"
draft: false
featured: false
---

Satcom NMS Toy is a deliberately small ground-segment design exercise. The project explores how a network-management-style service might ingest telemetry, validate strict protocol frames, track latest node state, generate alarms, schedule commands, and preserve an audit trail.

The repository is intentionally documentation-led at this stage. I am using it to practise requirements writing, interface definition, verification strategy, and the design of observable software before committing to implementation details.

Because it is a design-stage project, I present it as systems-design evidence rather than as a finished implementation.
