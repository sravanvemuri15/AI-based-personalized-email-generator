# 📧 AI-Driven Email Generation Prototype for SDR Tool

Automate personalized sales outreach with large language models and an agentic workflow!  
This project demonstrates how to use AI to generate highly tailored cold emails for leads using structured lead and product data, the HuggingFace Gemma 1B It model, LangChain, and CrewAI.

---

## 🚀 Features

- **Personalized Email Generation:** Uses lead roles, interests, and product features.
- **Modern LLM Integration:** Powered by HuggingFace’s open-source Gemma 1B It.
- **Agentic Reasoning:** Workflow orchestration via CrewAI agents and LangChain.
- **Easy Extensibility:** Add batching, custom prompts, tones, or integrate real APIs.
- **Reproducible Environment:** Deploy anywhere with Docker.

---

## 🧩 Project Structure

```plaintext
ai_email_gen/
├── app.py                   # Main script for loading data, LLM, generating emails
├── lead_product_sample.json # Example lead and product for demonstration
├── requirements.txt         # Python dependencies
└── Dockerfile               # For containerization
