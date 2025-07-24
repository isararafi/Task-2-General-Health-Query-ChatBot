# Health Query Chatbot 

A simple **General Health Query Chatbot** built in a **Jupyter Notebook** as part of my internship project.

This chatbot answers **general health-related questions** using a **Large Language Model (LLM)** with **prompt engineering** and a **medical safety filter** to ensure it does not give harmful or specific medical treatment advice.

---

## **Task Objective**

- Build a chatbot that can answer **general health-related questions**.
- Use **prompt engineering** to make responses clear, friendly, and safe.
- Integrate a **safety filter** to avoid giving medical advice that could be harmful.
- Demonstrate the use of an **LLM API** inside a **Python Jupyter Notebook**.
- Example queries tested include:
  - *“What causes a sore throat?”*
  - *“Is paracetamol safe for children?”*
  - *“What causes headaches?”*
  - *“What dosage of paracetamol is safe for a 20-year-old?”* (should trigger the safety filter)

---

## **Dataset Used**

**No static dataset** is used.  
The chatbot uses **real-time user input** and queries a live **Cohere LLM API** for each question.

---

## **Models Applied**

- **Model Used:** Cohere `command-nightly`  
- **Access Method:** Cohere’s official **REST API**
- **Interface:** Python code in a **Jupyter Notebook**

---

## **Key Results and Findings**

- ✅ Successfully implemented a working **health chatbot** that handles **general health questions**.
- ✅ Designed and tested **prompt engineering** to guide the LLM’s behavior.
- ✅ Verified the **medical safety filter** works: it blocks direct medical treatment instructions, dosages, and prescriptions.
- ✅ Demonstrated safe use of a **large language model** in a conversational assistant.
- ✅ Ready for internship submission with clean, well-commented code and clear documentation.

---

## **How to Run**

1. Clone or download this repository.
2. Open the `.ipynb` file in **Jupyter Notebook**.
3. Insert your **Cohere API key**:
   ```python
   COHERE_API_KEY = "YOUR_COHERE_API_KEY"
