
---

# 🤖 AI Chatbot - PDF-based Query Answering  
**Project developed during my internship at Vinci Energies & Axians**  

This project is a powerful AI chatbot that answers user queries by analyzing content from multiple PDF documents. The chatbot processes PDFs, extracts and analyzes the text, and delivers context-aware responses using **NLP** models and **document embeddings**. It runs on **Spring Boot 3.3.1**, does not use a traditional database, but utilizes **PVGStore** for model storage. 🚀

---

## ✨ Features  

- **Spring Boot 3.3.1** ⚙️: Backend framework to build scalable applications.
- **Tomcat Server** 🌐: Handles HTTP requests on **port 8080**.
- **React.js** ⚛️: Front-end for building dynamic and responsive interfaces.
- **Vaadin** 🧩: UI components for building elegant reactive web pages.
- **LLM (Large Language Models)** 🤖: Provides intelligent, context-aware responses.
- **Olama & RAG** 🔗: Retrieval-augmented generation for advanced query handling.
- **Spring AI** 🧠: For managing AI models.
- **PVGStore** 🗂️: Stores AI models and facilitates retrieval without a database.
- **Maven** ⚙️: Build tool for managing dependencies and project lifecycle.
- **REST API** 🌐: Allows interaction with the chatbot and PDFs through HTTP endpoints.

---

## ⚙️ How to Run  

1. **Clone** this repository to your machine.
2. Make sure **Spring Boot 3.3.1** is installed.
3. Start the application on **port 8080** using **Maven** or your IDE.  
   ```bash
   mvn spring-boot:run
   ```
4. Open your browser and access the chatbot via the **Tomcat Server** running on **port 8080**.  
   You can interact with the API or the UI directly.

---

## 💻 Technologies  

- **Spring Boot 3.3.1** ⚙️: Backend framework to build scalable applications.
- **Tomcat Server** 🌐: Handles HTTP requests on port 8080.
- **React.js** ⚛️: Front-end for building dynamic and responsive interfaces.
- **Vaadin** 🧩: UI components for building elegant reactive web pages.
- **LLM (Large Language Models)** 🤖: Provides intelligent, context-aware responses.
- **Olama & RAG** 🔗: Retrieval-augmented generation for advanced query handling.
- **Spring AI** 🧠: For managing AI models.
- **PVGStore** 🗂️: Stores AI models and facilitates retrieval without a database.
- **Maven** ⚙️: Build tool for managing dependencies and project lifecycle.
- **REST API** 🌐:  
  - **`POST /api/query`** 💬: Submit a question, receive context-aware AI responses.  

---

## 🚀 How It Works  

1. **Upload PDFs** 📄: Users can upload PDF files to the system.
2. **Query the AI** 💬: Ask questions, and the chatbot retrieves relevant sections from the uploaded PDFs.
3. **Context-Aware Responses** 🤖: Using **LLMs** and **RAG**, the system generates intelligent answers based on PDF content.

---

Enjoy the benefits of cutting-edge **AI** and **NLP** combined with modern web technologies to create an intuitive, efficient chatbot experience!

--- 

This project was developed as part of my internship at **Vinci Energies** & **Axians**. 🎓
