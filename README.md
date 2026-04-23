# llm-response-stability-analysis
Large Language Models (LLMs) may generate varying responses even if their prompts differ slightly. This project aims to explore how different prompts affect response consistency and analyze the contradictions in generated text.
# LLM Response Stability and Contradiction Patterns

# 🔬 LLM Prompt Consistency Study  
### Testing the Effects of Prompt Variations on Responses from Large Language Models

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Status](https://img.shields.io/badge/Status-Research_Project-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🧠 Overview
Large Language Models (LLMs) may generate varied responses based on differences in prompt wording.  
This research examines the impact of **prompt sensitivity, response consistency, and reliability**.

---

## 🎯 Objectives
- Assess the influence of different prompts on the outputs of LLMs  
- Determine **response consistency by comparing semantic similarity**  
- Examine LLM behavior during adversarial prompts  
- Explore methods for enhancing reliability  

---

## 🧪 Experimental Setup
- 50 prompts (factual & reasoning questions)  
- 4-5 versions per prompt  
- Approximately 250 responses  

---

## ⚙️ Approach

### 🔹 Prompt Variations
- Standard  
- Rephrased  
- Adversarial  
- Organized  

### 🔹 Semantic Similarity Analysis
- Model: Sentence Transformers (`all-MiniLM-L6-v2`)  
- Similarity: Cosine Similarity  
- Procedure: Pairwise comparison among generated responses  

---

## 📊 Results

| Prompt Category   | Average Similarity |
|------------------|-------------------|
| Standard         | ~0.90+            |
| Rephrased        | ~0.80 - 0.85      |
| Adversarial      | ~0.60 - 0.70      |
| Organized        | ~0.88 - 0.91      |

💥 Adversarial prompts decrease stability, whereas organized prompts
