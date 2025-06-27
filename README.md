# Cold-Email-Generator

Cold email generator for **undergraduate students** using **Groq**, **LangChain**, and **Streamlit**.  

It allows students to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails tailored for student applications. These emails include relevant portfolio or project links sourced from a vector database, based on the specific job descriptions.

---
## 💡 Imagine a scenario:

Nike is hiring a **Principal Software Engineer** and has open roles listed on their careers page.  

Anami is a **final-year undergraduate student** actively seeking software engineering opportunities. Instead of applying generically, she wants to send a **personalized cold email** that shows she understands the role, aligns her skills to their needs, and shares relevant projects.  

This app helps Anami quickly generate such emails, saving time while increasing her chance of getting noticed.

---


![Screenshot 2025-06-27 193358](https://github.com/user-attachments/assets/010caad7-6897-425f-8d28-a7c76573c371)


## ⚙️ Set-up
1. To get started you first need to get an API_KEY from here:  
   [https://console.groq.com/keys](https://console.groq.com/keys).  

   Inside `app/.env`, update the value of `GROQ_API_KEY` with the API_KEY you created.

---

2. ### ✅ Install the dependencies using:
   ```bash
   pip install -r requirements.txt
   
---
## ✅ Run the Streamlit app:

```bash
streamlit run .\app\main.py

