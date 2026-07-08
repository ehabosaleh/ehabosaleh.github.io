---
title: "A Dedicated CPU Core for MPI Progress: Towards Improved Overlap in Non-blocking Two-sided Communication"
collection: talks
type: "Conference Presentation"
permalink: /talks/2026-ispdc-hamburg
venue: "IEEE International Symposium on Parallel and Distributed Computing (ISPDC)"
date: 2026-07-01
location: "Hamburg, Germany"
---

Presented research on reserving a dedicated CPU core for both communication progress and data transfer in non-blocking two-sided MPI communication.
The main contribution of this work is the use of proxy multi-threaded memory copies between sender and receiver buffers in shared-memory environments. 
The approach was evaluated using both communication-computation overlap ratio and energy consumption measurements for the CPU package and DRAM.
