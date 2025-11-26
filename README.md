# LLM Red Teaming Audit Demo

## Project Overview

A comprehensive security assessment of a Financial Services Chatbot ("ZephyrBank") and an E-Commerce Agent ("ByteChapters").

**Scope:** Manual probing, automated scanning (Giskard), and adversarial simulation identified 16 distinct vulnerabilities across the OWASP Top 10 for LLMs.

## Key Findings

- **Critical:** Business Logic Bypass leading to financial fraud.
- **High:** PII Leakage and System Prompt Extraction.

## Tools Used

Python, Giskard, OpenAI API.

## Repository Structure

```
📂 LLM-Red-Teaming-Audit-Demo
├── 📄 ASSESSMENT_LOG.md  (Detailed vulnerability findings)
├── 📄 README.md          (This executive summary)
└── 📂 notebooks/         (Evidence notebooks L1-L5)
    ├── L1_Overview_of_LLM_vulnerabilities.ipynb
    ├── L2_Red_teaming_LLMs.ipynb
    ├── L3_Red_teaming_at_scale.ipynb
    ├── L4_Red_teaming_LLMs_with_LLMs.ipynb
    └── L5_A_full_red_teaming_assessment.ipynb
```

## Vulnerability Summary

- **16 vulnerabilities** identified across multiple attack vectors
- **4 Critical** severity findings (System compromise, Financial fraud)
- **6 High** severity findings (Data leakage, Bias, Misinformation)
- **6 Medium** severity findings (DoS, Guardrail bypass)

## Methodologies Applied

1. **Manual Red Teaming** - Direct prompt injection and social engineering
2. **Automated Scanning** - Giskard LLM security assessment
3. **Adversarial AI** - LLM-vs-LLM automated attack generation
4. **Full Assessment** - End-to-end security evaluation of production-like systems

## 🎓 Methodology & Coursework

This project serves as a capstone for the **"Red Teaming LLM Applications"** curriculum by **DeepLearning.AI** and **Giskard**.

**Technical Scope:**
The engagement simulates a full-lifecycle security audit on RAG-based chat agents, progressing from manual exploitation to automated adversarial testing.

**Core Competencies Demonstrated:**

- **Manual Red Teaming:** Exploiting Logic Flaws, Hallucinations, and PII Leaks.
- **Advanced Prompt Engineering:** Utilizing "Do Anything Now" (DAN) payloads, Prefix Injection, and Context Manipulation.
- **Automated Scanning:** Configuring the **Giskard** framework to detecting hidden vulnerabilities (Sycophancy, Toxicity) at scale.
- **Adversarial AI:** Orchestrating LLM-vs-LLM attacks where an "Attacker Agent" generates probes to break a "Victim Agent".
- **Business Logic Auditing:** Identifying domain-specific flaws (e.g., Refund Fraud) in a simulated e-commerce environment.

**Attribution:**

- **Course Provider:** [DeepLearning.AI](https://www.deeplearning.ai/)
- **Tooling Framework:** [Giskard AI](https://giskard.ai/)
- **Instructors:** Matteo Dora & Luca Martial

## ⚖️ License & Attribution

**The Assessment Log and Custom Vulnerability Reports:**
Copyright © 2025 [Your Name]. This work is licensed under [MIT](LICENSE) (for code) and [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) (for documentation). You are free to share and adapt this work with attribution.

**Course Materials (Notebooks & Helper Files):**
This repository contains educational materials from the [DeepLearning.AI "Red Teaming LLM Applications"](https://www.deeplearning.ai/) course.

- **Original Code & Labs:** Copyright © DeepLearning.AI & Giskard.
- **Usage:** These files are included for educational demonstration and portfolio context only. They are not licensed for commercial use or redistribution.
