<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5C4033,100:6B8E23&height=200&section=header&text=Rofaida%20Khaled&fontSize=45&fontColor=F5F0E6&animation=fadeIn&fontAlignY=38&desc=Data%20Scientist%20%7C%20Machine%20Learning%20Engineer&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Georgia&size=20&duration=3000&pause=1000&color=6B8E23&center=true&vCenter=true&width=600&lines=Building+AI-powered%2C+data-driven+solutions;Machine+Learning+%7C+NLP+%7C+RAG+Systems;Big+Data+%7C+Data+Warehousing+%7C+Python" alt="Typing SVG" />

<br/>

<a href="mailto:rofaida.khaled1111@gmail.com"><img src="https://img.shields.io/badge/Email-5C4033?style=for-the-badge&logo=gmail&logoColor=F5F0E6" /></a>
<a href="#"><img src="https://img.shields.io/badge/LinkedIn-6B8E23?style=for-the-badge&logo=linkedin&logoColor=F5F0E6" /></a>
<a href="#"><img src="https://img.shields.io/badge/GitHub-808000?style=for-the-badge&logo=github&logoColor=F5F0E6" /></a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## About Me

I'm a Data Science graduate (IT Software, Borg El Arab Technological University) with hands-on experience across **Machine Learning, NLP, Retrieval-Augmented Generation (RAG), Big Data, and Data Warehousing**. I like building things end-to-end — from raw data pipelines to production-ready AI applications with real users.

- 🔭 Currently building full-stack AI applications powered by LLMs and RAG pipelines
- 🌱 Deepening my knowledge of Machine Learning and applied NLP
- 🎯 Passionate about solving real business problems with data-driven and AI-powered solutions
- 🎓 Graduating July 2026

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## Skills

<div align="center">

**Programming**
<br/>
<img src="https://img.shields.io/badge/Python-5C4033?style=flat-square&logo=python&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/Java-6B8E23?style=flat-square&logo=openjdk&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/C++-808000?style=flat-square&logo=cplusplus&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/C-5C4033?style=flat-square&logo=c&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/PHP-6B8E23?style=flat-square&logo=php&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/JavaScript-808000?style=flat-square&logo=javascript&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/SQL-5C4033?style=flat-square&logo=postgresql&logoColor=F5F0E6"/>

**Data & Machine Learning**
<br/>
<img src="https://img.shields.io/badge/Machine%20Learning-6B8E23?style=flat-square&logo=scikitlearn&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/NLP-808000?style=flat-square&logo=spacy&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/RAG-5C4033?style=flat-square&logo=openai&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/Pandas-6B8E23?style=flat-square&logo=pandas&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/NumPy-808000?style=flat-square&logo=numpy&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/Scikit--learn-5C4033?style=flat-square&logo=scikitlearn&logoColor=F5F0E6"/>

**Big Data & Engineering**
<br/>
<img src="https://img.shields.io/badge/Apache%20Kafka-6B8E23?style=flat-square&logo=apachekafka&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/ETL-808000?style=flat-square&logo=databricks&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/Data%20Warehousing-5C4033?style=flat-square&logo=snowflake&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/PostgreSQL-6B8E23?style=flat-square&logo=postgresql&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/SQLite-808000?style=flat-square&logo=sqlite&logoColor=F5F0E6"/>
<img src="https://img.shields.io/badge/Power%20BI-5C4033?style=flat-square&logo=powerbi&logoColor=F5F0E6"/>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 🚀 Featured Project — BATU AI BOOT

<div align="center">
<img src="https://img.shields.io/badge/Status-Production-6B8E23?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Type-RAG%20Chatbot-5C4033?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Language-Arabic%20%26%20English-808000?style=for-the-badge"/>
</div>

**Intelligent university chatbot** built as the official AI assistant for Borg El Arab Technological University — answering student questions about faculties, admissions, fees, and activities using real data from the university website.

The core of the system is a **RAG (Retrieval-Augmented Generation) pipeline**: instead of relying on the LLM's general knowledge, it first retrieves the most relevant context from a structured knowledge base using **TF-IDF + cosine similarity**, then passes that grounded context to the LLM — virtually eliminating hallucination.

**Highlights**
- 🤖 Conversational assistant powered by **LLaMA 3.3 70B** via the Groq API
- 🔍 Custom **RAG retrieval pipeline** (TF-IDF cosine similarity) run before every LLM call
- ⚡ FAQ caching for instant responses on repeat questions — no API call needed
- 🕌 Arabic-first NLP normalization (alef variants, teh marbuta, diacritics, stopwords) for Egyptian dialect + MSA
- 🔐 3-level access control: Guest → Registered Student → Admin
- 🛡️ Production-grade security: rate limiting, bcrypt password hashing, secure sessions, `.htaccess` protection, atomic file writes, SQLite in WAL mode

<details>
<summary><b>Tech Stack</b></summary>
<br/>

| Layer | Technologies |
|---|---|
| Backend | PHP 8.1+, SQLite 3 (WAL mode), PDO, cURL |
| AI / NLP | Groq API, LLaMA 3.3 70B, TF-IDF, Cosine Similarity, RAG |
| Frontend | HTML5, CSS3, Vanilla JavaScript, Marked.js |
| Security | Rate limiting, bcrypt, httpOnly/SameSite sessions, `.env` secrets |

</details>

<div align="center">
<img src="https://img.shields.io/badge/View_Project-6B8E23?style=for-the-badge&logo=github&logoColor=F5F0E6"/>
</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 📂 Other Projects

<table>
<tr>
<td width="50%" valign="top">

### 🖐️ Sign Language Recognition
Real-time system translating hand gestures into readable text using MediaPipe hand-landmark extraction and a Random Forest classifier.
<br/>
<img src="https://img.shields.io/badge/Python-5C4033?style=flat-square"/> <img src="https://img.shields.io/badge/OpenCV-6B8E23?style=flat-square"/> <img src="https://img.shields.io/badge/MediaPipe-808000?style=flat-square"/>

</td>
<td width="50%" valign="top">

### 📊 Big Data Sales Analytics Pipeline
Real-time sales data streaming with Kafka, a Star Schema data warehouse, ETL processes, and interactive Power BI dashboards.
<br/>
<img src="https://img.shields.io/badge/Kafka-5C4033?style=flat-square"/> <img src="https://img.shields.io/badge/PostgreSQL-6B8E23?style=flat-square"/> <img src="https://img.shields.io/badge/Power%20BI-808000?style=flat-square"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 Health Essentials — Data Analysis
Cleaned and analyzed healthcare sales data with exploratory analysis and interactive Power BI dashboards for business insights.
<br/>
<img src="https://img.shields.io/badge/Python-5C4033?style=flat-square"/> <img src="https://img.shields.io/badge/Power%20BI-6B8E23?style=flat-square"/> <img src="https://img.shields.io/badge/Pandas-808000?style=flat-square"/>

</td>
<td width="50%" valign="top">

### 🎙️ AI Assistant Robot (Echo)
Voice-controlled academic assistant integrating speech recognition and NLP for automated academic task assistance.
<br/>
<img src="https://img.shields.io/badge/Python-5C4033?style=flat-square"/> <img src="https://img.shields.io/badge/NLP-6B8E23?style=flat-square"/> <img src="https://img.shields.io/badge/Speech%20Recognition-808000?style=flat-square"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔥 IoT Smart Fire-Extinguishing Robot
Smart robotic solution using Arduino for automated fire detection and safety response.
<br/>
<img src="https://img.shields.io/badge/Arduino-5C4033?style=flat-square"/> <img src="https://img.shields.io/badge/C++-6B8E23?style=flat-square"/> <img src="https://img.shields.io/badge/IoT-808000?style=flat-square"/>

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 💼 Experience

- **Ambassador**, EME Innovation Hub, Borg El Arab — *2023 – Present*
- **Coding Instructor**, Jupiter Academy — *Mar 2024 – Jul 2024*
- **NLP Intern**, Bibliotheca Alexandrina, Alexandria
- **Machine Learning for Data Analysis**, NTI

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## 📫 Get in Touch

<div align="center">

<a href="mailto:rofaida.khaled1111@gmail.com"><img src="https://img.shields.io/badge/rofaida.khaled1111@gmail.com-5C4033?style=for-the-badge&logo=gmail&logoColor=F5F0E6"/></a>
<a href="www.linkedin.com/in/rofaida-khaled505"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-6B8E23?style=for-the-badge&logo=linkedin&logoColor=F5F0E6"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6B8E23,100:5C4033&height=100&section=footer" width="100%"/>

</div>
