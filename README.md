# Digital Logic & AI Evaluation (CSNS 141)

This repository tracks my study of hardware-level logic and its application to **AI Safety** and **Red-Teaming**.

### 🔍 Logic Gate Verification: XOR Gate
In Cyber Security, the **XOR (Exclusive OR)** gate is critical for encryption (like the One-Time Pad). In AI training, I use this logic to identify contradictory model outputs.

| Input A | Input B | XOR Output ($A \oplus B$) |
| :---: | :---: | :---: |
| 0 | 0 | **0** |
| 0 | 1 | **1** |
| 1 | 0 | **1** |
| 1 | 1 | **0** |

> **Note:** The output is high ($1$) only when the inputs are different. If an AI provides two logically identical but labeled differently responses, it violates this basic logic.
