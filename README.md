# Silicon Stencil Lab

Research and test notes from [Silicon Stencil](https://siliconstencil.com).
Each folder is one self-contained experiment: what was tried, on what
hardware, what came out, and how to repeat it. Negative and inconclusive
results are written up the same way as successful ones.

| date | experiment | hardware | result |
|---|---|---|---|
| 2026-03-28 | [32K context with TurboQuant KV-cache compression in vLLM](vLLM-TurboQuant-32K-Success/) | RTX 4070 Laptop, 8 GB | works: Llama 3.1 8B (Q4_K_M) at 32,768 tokens, ~23 tok/s |

Notes are shared as they are, for anyone who needs the result. If something
does not reproduce on your setup, open an issue with your hardware and versions.
