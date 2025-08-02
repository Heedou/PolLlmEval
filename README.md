# PAS: Police Action Scenario Framework

**PAS (Police Action Scenario)** is a dedicated framework for evaluating Large Language Models (LLMs) in real-world policing contexts.

Modern policing requires nuanced judgment and situational awareness—standard benchmarks alone are not sufficient. PAS introduces a scenario-based, multi-stage evaluation method designed specifically for policing tasks.

## 🔍 Evaluation Pipeline

<img width="1000" height="700" alt="FIg1-PAS Construction with Example" src="https://github.com/user-attachments/assets/672a5982-cfcc-4e06-a2d6-2b56646b62af" />


PAS defines LLM evaluation as a five-stage process:

- **S: Police Action Scenarios**  
  Situation-driven tasks reflecting real-world policing needs.

- **R: Reference Responses**  
  Expert-crafted gold answers created with input from law enforcement professionals.

- **G: Response Generation**  
  LLM-generated outputs based on the given scenarios.

- **M: Core Evaluation Metrics**  
  Task-relevant metrics and evaluation methodologies tailored for public safety applications.

- **P: Policing LLM Performance Evaluation**  
  Final assessment of the LLM’s effectiveness, accuracy, and fitness for deployment in policing.

Formally expressed as:  
`E_police = f(S, R, G, M, P)`

---

> PAS fills the gap in evaluating LLMs for law enforcement by combining structured scenarios, expert benchmarks, and targeted metrics.
