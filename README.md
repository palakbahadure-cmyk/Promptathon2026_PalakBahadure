# Promptathon2026_PalakBahadure
PROBLEM STATEMENT:VIRTUAL AI ASSISTANT 

DOMAIN : HEALTHCARE

AI TOOL USED:CLAUDE

PROMPT GIVEN : build the AI where you act like a doctor and guide user as a patient before that you give the recommendation of appointment after that according to 
users appointment based on first came first preferance to meet you and analye user based on symptoms and asked questions and give the health suggestions what to 
do next and give prescriptions based on analysis

# 🩺 Agentic AI Healthcare Assistant & Consultation System

An interactive, agentic AI-powered virtual intake and consultation system. Built to simulate a real-time doctor-patient interaction, the system combines dynamic conversational triage, automated first-come, first-served appointment queuing, multi-layered emergency safety checks, and personalized health recommendations.

---

## ✨ Features

### 🤖 Agentic AI Triage & Adaptive Dialogue
- **Dynamic Reasoning Engine:** Uses Claude API to ask targeted, context-aware follow-up questions tailored to specific symptoms (e.g., respiratory, digestive, skin, or injury).
- **Natural Back-and-Forth:** Simulates a realistic intake interview rather than forcing users through rigid form inputs.

### ⏱️ Automated First-Come, First-Served Queue
- Assigns real-time queue numbers upon check-in.
- Features a dynamic waiting room dashboard that displays real-time position updates and current ticket calls.

### 🚨 Autonomous Emergency Guardrails & Red-Flag Intercept
- **Multi-Tier Safety Architecture:** Combines AI reasoning with local keyword detection to identify high-risk symptoms (e.g., severe chest pain, stroke symptoms, acute shortness of breath).
- **Immediate Escalation:** Halts the AI conversation instantly when an emergency state is detected, routing the patient to local emergency services without delay.

### 📄 Comprehensive Visit Summaries
- Automatically generates a structured "Health Note" upon session completion.
- Outlines category-level OTC comfort measures, hydration/rest protocols, and specific "When to See a Clinician" thresholds.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+ / Modern Web APIs)
- **AI Core:** Anthropic Claude API (Agentic Conversational Pipeline)
- **State Management:** Client-side local storage / In-memory queue state management

---

## 🚀 Getting Started

### Prerequisites

- A modern browser (Chrome, Firefox, Edge, Safari).
- An active **Anthropic API Key** (required for agentic AI interaction).

### Quick Start

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/your-username/agentic-ai-healthcare.git](https://github.com/your-username/agentic-ai-healthcare.git)
   cd agentic-ai-healthcare
