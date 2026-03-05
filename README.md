# Digital Logic & AI Evaluation (CSNS 141)

This repository tracks my study of hardware-level logic and its application to **AI Safety** and **Red-Teaming**.

### 🔍 Logic Gate Verification: OR Gate
The **OR gate** represents a logical disjunction. In the context of **AI Model Evaluation**, we use OR logic to ensure that a model's response satisfies at least one of several acceptable criteria (e.g., being either "Informative" OR "Concise").

| Input A | Input B | OR Output ($A + B$) |
| :---: | :---: | :---: |
| 0 | 0 | **0** |
| 0 | 1 | **1** |
| 1 | 0 | **1** |
| 1 | 1 | **1** |

> **Note:** The output is "High" ($1$) if one or both inputs are true. It only fails ($0$) if the model fails to meet **all** required criteria.

### 🔍 Logic Gate Verification: XOR Gate
In Cyber Security, the **XOR (Exclusive OR)** gate is critical for encryption (like the One-Time Pad). In AI training, I use this logic to identify contradictory model outputs.

| Input A | Input B | XOR Output ($A \oplus B$) |
| :---: | :---: | :---: |
| 0 | 0 | **0** |
| 0 | 1 | **1** |
| 1 | 0 | **1** |
| 1 | 1 | **0** |

> **Note:** The output is high ($1$) only when the inputs are different. If an AI provides two logically identical but labeled differently responses, it violates this basic logic.
