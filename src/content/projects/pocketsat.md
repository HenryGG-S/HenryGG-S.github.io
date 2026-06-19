---
title: "PocketSat"
description: "A small satellite-inspired embedded avionics trainer for practising telemetry, command handling, mode management, fault response, and verification discipline."
date: 2026-06-01
tags: ["embedded-c", "stm32", "telemetry", "fault-handling", "systems", "space-software"]
repo: "https://github.com/HenryGG-S/pocketsat/"
draft: false
featured: true
---

PocketSat is a personal embedded systems project built around the idea of a small, spacecraft-inspired avionics trainer. The aim is not to simulate a full satellite, but to practise the engineering habits that matter in embedded and mission-adjacent software: explicit state, clear commands, observable telemetry, fault response, and written verification evidence.

The current Mk1 implementation targets an STM32 Nucleo-F401RE using STM32Cube/HAL and PlatformIO. It includes a line-based UART command interface with documented `ACK`, `DENY`, and `REJECT` behaviour, bounded command handling, explicit mode transitions, SAFE-mode enforcement, sensor health checks, IMU sampling, LCD status output, structured ASCII telemetry, and a binary HEALTH telemetry baseline with a host-side decoder.

I also used the project to practise fault-detection and recovery behaviour, including explicit fault states, task-age diagnostics, watchdog-gated liveness supervision, deliberate watchdog reset testing, and reset-cause reporting on reboot.

The project is documented with ECSS-inspired requirements, a packet specification, command reference, coding standard, verification notes, test reporting, release notes, and closure documentation.
