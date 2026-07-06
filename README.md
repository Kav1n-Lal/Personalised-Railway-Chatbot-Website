# 🚆 Personalised Railway Chatbot Website

An AI-powered railway assistant that provides intelligent, personalized responses to user queries using **Gemma (via Ollama)**, **LangGraph**, and **FastAPI**. The system leverages a public railway dataset and tool-calling capabilities to deliver accurate, real-time information in a conversational format.

---
## For queries and project files mail to - kavingilbert@gmail.com

##  Project Video Links
- Entire Project Explanation-[https://drive.google.com/file/d/18uJU8hoFmvfJdgrxd8JkLrfdPT6yLueX/view?usp=sharing]
- Chatbot Website Demo-[https://drive.google.com/file/d/11ofB4xVF26MwI-I1A7mkj1zi4ikXG--f/view?usp=sharing]

##  Screenshots
<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/8aed0b26-2298-4900-a50f-dc428f73d015" /> <br>
<b>Register Page</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/a9a8d047-0b3d-40e7-bc8b-61b9e4d8aaec" /> <br>
<b>Login Page</b>
</td>
</tr>
</table>
<img width="1920" height="1080" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/2d7e4987-8e15-45de-84cb-e5def052c1e8" />
<img width="1920" height="1080" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/188de6ec-f6f6-407b-9eff-5c7bddd83a73" />

##  Chat UI Screenshots
<img width="1920" height="1080" alt="Screenshot (98)" src="https://github.com/user-attachments/assets/d483bdc0-d61a-4d9a-be79-6294c3ed6243" />
<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/8e26c7f0-ee8e-40a6-a7ef-b75a702ac9ed" /> <br>
<b>Chat Interactions 1</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/25cb9432-e262-4151-9d80-80bfe42e2b71" /> <br>
<b>Chat Interactions 2</b>
</td>
</tr>
</table>

## 📌 Features

- 🔐 User Registration & Login system
- 🔑 JWT-based authentication (secure token-based access)
- 💬 Conversational railway chatbot interface
- 🧠 Powered by **Gemma LLM (Ollama)**
- 🧩 Tool-calling for structured railway dataset queries
- 📊 Data processing using Pandas
- 🌐 Web-based UI using HTML, CSS, and JavaScript
- ⚙️ Backend built with FastAPI
- 🔄 LangGraph-based agent workflow for intelligent decision making

---

## 🏗️ System Architecture
Frontend (HTML/CSS/JS)
-->
FastAPI Backend (Auth + Routes)
-->
JWT Authentication Layer
-->
LangGraph Agent Controller
-->
Tool Calling System
-->
Railway Dataset (Pandas)
-->
Gemma LLM (Ollama)
-->
Final Response to User

## 🔄 LangGraph Workflow
User Query
-->
Intent Detection (Router Node)
-->
Decision: Tool Required?
If No → Direct LLM Response (Gemma)
//If Yes
-->
Railway Data Tool (Pandas Query)
-->
Structured Result
-->
Response Generation (Gemma)
-->
Final Answer

<img width="290" height="290" alt="images" src="https://github.com/user-attachments/assets/6354b531-41fb-444f-99df-dab62e048857" />
---

## 🧰 Tech Stack

**Backend**
- Python
- FastAPI

**AI / LLM**
- Gemma (via Ollama)
- LangGraph
- Tool Calling

**Data Processing**
- Pandas

**Frontend**
- HTML
- CSS
- JavaScript

**Authentication**
- JWT (JSON Web Tokens)
- FastAPI Security

---


---

## 🔐 Authentication Flow

1. User registers with credentials  
2. Password is securely hashed and stored  
3. On login, JWT token is generated  
4. Token is stored in browser cookies  
5. Each request is validated using the token  
6. Unauthorized users are redirected to login page  

---

## 📊 Dataset

- Public railway dataset used as knowledge base  
- Contains:
  - Train details
  - Source & destination stations
  - Timings
  - Route information  

---


