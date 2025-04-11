# 🤖 Exploring Prompt Engineering & Tool-Augmented Agents with LLMs

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![OpenAI API](https://img.shields.io/badge/OpenAI-API-orange)](https://platform.openai.com/)
[![Gentopia-Mason](https://img.shields.io/badge/Gentopia-Mason-blueviolet)](https://github.com/aditya-sudo/Gentopia-Mason.git)

## 📚 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Key Objectives](#-key-objectives)
- [🧪 Technologies Used](#-technologies-used)
- [⚙️ Features Implemented](#️-features-implemented)
- [📚 Learning Outcomes](#-learning-outcomes)
- [👨‍💻 Author](#-author)

---

## 📌 Project Overview

This project delves into the practical capabilities of **large language models (LLMs)** through two key areas:

1. **Prompt Engineering and Language Understanding**: Using the OpenAI API for story generation, mathematical reasoning, and behavioral tuning with different sampling strategies (`top-p`, temperature).
2. **LLM Agent Development with Gentopia**: Creating both **vanilla and tool-augmented LLM agents**, enhancing them with external capabilities such as Google Scholar search, PDF summarization, and web-based data retrieval.

---

## 🎯 Key Objectives

- Develop prompt templates and observe their impact on LLM outputs.
- Compare different sampling techniques (`top-p`) and analyze their influence on content diversity.
- Evaluate reasoning abilities of LLMs in solving mathematical word problems.
- Build LLM agents using the **Gentopia-Mason** framework ([GitHub Repo](https://github.com/aditya-sudo/Gentopia-Mason.git)) with access to:
  - Scholarly search tools
  - PDF readers
  - Web-based research augmentation
- Create a wellness agent with meditation, nutrition, and speech synthesis features.

---

## 🧪 Technologies Used

- OpenAI API (gpt-4o-mini)
- Python, PyTorch
- Gentopia-Mason framework
- PyPDF2, `scholarly` for academic search
- Google Colab, Jupyter Notebook

---

## ⚙️ Features Implemented

- Custom prompts for narrative generation & analysis
- Few-shot prompting for reasoning consistency
- Custom Gentopia agents:
  - **Scholar Agent** (Google Scholar + PDF summarizer)
  - **Wellness Agent** (nutrition planner, mindfulness exercises, text-to-speech)
- YAML-based configuration of agent workflows

---

## 📚 Learning Outcomes

- Improved understanding of how temperature, top-p, and few-shot prompting affect LLM behavior
- Hands-on experience with open-source frameworks for **LLM agent creation**
- Realized the limitations of LLMs in isolation and the value of tool augmentation
- Built usable agents capable of providing scholarly data, wellness insights, and language reasoning

---

## 👨‍💻 Author

Aditya Ketanbhai Shah  
CS 678: Advanced NLP (Fall 2024) – George Mason University  
