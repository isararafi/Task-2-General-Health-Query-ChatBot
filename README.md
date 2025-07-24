# Health Query Chatbot 🤖✨

A simple **General Health Query Chatbot** built in a **Jupyter Notebook** for my internship task.

This chatbot uses the **Cohere LLM API** to answer **general health-related questions** using **prompt engineering** to ensure **safe, friendly, clear** responses without giving specific medical advice.

---

## **Task Objective**

- Build a chatbot that answers **general health questions**.
- Use **prompt engineering** to keep responses clear, friendly, and **safe**.
- Add a **safety filter** to avoid giving harmful or specific medical treatment advice.
- Example queries:  
  - *“What causes a sore throat?”*  
  - *“Is paracetamol safe for children?”*  
  - *“What are symptoms of the flu?”*

---

## **How It Works**

- **Language Model**: Uses **Cohere’s `command-nightly`** model via the Cohere API.
- **Jupyter Notebook**: All code is in a single `.ipynb` file — easy to run step by step.
- **Prompt Engineering**: A `preamble` guides the chatbot to:
  - Answer only **general** questions.
  - Never give **specific dosages or treatments**.
  - Always recommend consulting a **qualified doctor**.
- **Conversation Loop**: Users can interactively ask multiple questions in one run.

---

## ✅ **Key Skills Demonstrated**

- 🗂️ **Prompt Design**
- 🔗 **Using an LLM API**
- 🛡️ **Safety Handling**
- 💬 **Simple Conversational Logic**

---

## ⚠️ **Important Note**

**This chatbot is for educational purposes only.**  
It does **NOT** give professional medical advice.  
**Always consult a qualified healthcare provider** for any medical questions or treatment.

---

## 🚀 **How to Run**

1. Clone or download the repository.
2. Open the `.ipynb` in **Jupyter Notebook**.
3. Insert your **Cohere API key** in the designated cell:
   ```python
   
