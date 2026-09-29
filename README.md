# 🏥 MedTech Deal Intelligence Agent

> An AI-powered enterprise sales execution and deal-tracking platform built for **HackwithHyderabad 3.0**. 

---

## 🚀 Overview
Enterprise medical technology sales cycles are notoriously complex, long-term, and fraught with recurring compliance hurdles (FDA, HIPAA), pricing pushback, and aggressive competitor pressure. Traditional sales tools rely on stateless chatbots that reset after every call, forcing sales reps to manually dig through fragmented CRM notes.

The **MedTech Deal Intelligence Agent** solves the "stateless chatbot" problem by integrating **Vectorize Hindsight** as a persistent memory engine alongside **Groq** for high-speed LLM inference. The agent securely logs, recalls, and evolves based on historical stakeholder interactions, prior objections, and multi-stage deal progression.

---

## 🧠 Core Features & Architecture

* **Persistent Memory Layer (Powered by Vectorize Hindsight):** Automatically stores and recalls historical clinical objections, budget constraints, and compliance notes across weeks of sales cycles.
* **Real-Time Memory Audit Stream:** An interactive UI sidebar that allows judges and users to visually inspect what memory vectors are being retrieved in real time.
* **Dynamic Deal Win-Probability Analytics:** Computes and displays real-time win-rate metrics, showcasing a clear before-and-after contrast when memory is enabled vs. disabled.
* **Automated Executive Follow-Up Generator:** One-click generation of high-conversion post-call client emails tailored to specific stakeholder concerns.
* **Lightning-Fast Inference:** Powered by **Groq** for low-latency, real-time responses during live high-stakes sales pitches.

---

## 🛠️ Tech Stack

* **Frontend / UI:** Streamlit (Custom Enterprise Dark-Mode Dashboard)
* **LLM Provider:** Groq API (`openai/gpt-oss-20b`)
* **Persistent Memory:** Vectorize Hindsight Client (`hindsight-client`)
* **Language:** Python 3.10+

---

## ⚙️ Local Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/ramireddyjahnavi195-rjs/MedTech-Deal-Intelligence-Agent.git](https://github.com/ramireddyjahnavi195-rjs/MedTech-Deal-Intelligence-Agent.git)
   cd MedTech-Deal-Intelligence-Agent
