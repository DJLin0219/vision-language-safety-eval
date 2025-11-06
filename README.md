# SafeVLM: Fine-Tuning and Evaluation Framework for Vision-Language Models

This repository provides a **sample implementation** inspired by my prior internship work on **vision-language model (VLM) benchmarking and fine-tuning** for safety-critical perception tasks (e.g., traffic light and scene understanding).  
All data and code are **synthetic** and intended solely for **research demonstration** purposes.

---

## 🔍 Overview

This project presents a reproducible framework for **fine-tuning**, **evaluating**, and **benchmarking** modern Vision-Language Models (VLMs) on perception-aligned tasks.  
The design focuses on *robustness under visual uncertainty* and *cross-modal consistency*, resembling the core ideas used in large-scale safety perception evaluation pipelines.

### Key Features
- 🧠 **VLM Integration Layer** — unified interface for models such as LLaVA-NeXT, PaliGemma, Fuyu, InternVideo2.
- 🎯 **Fine-tuning Pipeline** — modular PyTorch pipeline for supervised or instruction-tuned adaptation using multimodal data.
- 📈 **Evaluation Metrics** — supports visual-textual accuracy, consistency, and reasoning alignment metrics.
- 🧩 **Prompt and Response Benchmarking** — evaluates LLM reasoning coherence under degraded perception (e.g., low-light or occluded scenes).
- ⚡ **Fully open and synthetic** — no private datasets or internal assets are included.

---

## 🧰 Repository Structure
