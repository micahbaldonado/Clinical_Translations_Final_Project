# Clinical Translations Final Project: AI Emotional Companion
### Note to my teammates: will change name once class ends so you guys can fork this!

> **HUGE THANKS** to **Kity**, **Kristi**, and **Renu** for their incredible support in building the website and for being such a huge inspiration!!!  
> This project was originally created for the **AI Agents Competition** hosted by the **CMU Data Science Club** .
> > 🧠 **AI AGENTS WEEKEND — April 12–13, 2025**
>
>  Since this competition, I created additional validation to show that an analysis module increases an LLM's capacity for empathy and genuine connection with the user.

---

## 🧠 About the Project

This repository contains the full codebase for my final report in **Clinical Translations** at Carnegie Mellon University. The project is a working prototype of an AI-powered **Emotional Companion**—a chatbot designed to engage with users in an emotionally intelligent and empathetic way.

The project was deployed on a full-stack website with the following features:

- ✅ A form-based onboarding system that tailors the model to the user
- ✅ Daily **mood tracking**
- ✅ An **open journaling** interface
- ✅ A **ChatGPT-style chat** experience that’s emotionally aware

> While the backend is currently **offline**, this repository includes all necessary code and structure to re-deploy locally or on a server.

---

## 🙌 Contributions

- **Micah Baldonado**
  - Originated the idea and led project development
  - Designed the AI model architecture and sentiment analysis pipeline
  - Validated the model’s improvement in empathetic responses
  - Collaborated on backend API integration and testing

- **Kristi**
  - Developed the entire frontend experience
  - Crafted the about-user form at the beginning of the website
  - Designed and implemented the journaling and mood tracking UI
  - Created an intuitive and clean user experience

- **Kity**
  - Implemented the backend infrastructure and API logic
  - Ensured sound backend logic to handle communication between front-end and the original model 
  - Worked with Micah to ensure smooth frontend-backend communication

- **Renu**
  - Designed our group’s presentation slides for the AI Agents competition
  - Played a key role in communicating the project vision clearly to judges and peers

---

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/micahbaldonado/Clinical_Translations_Final_Project.git
cd Clinical_Translations_Final_Project
```

### 2. Set Up Your Environment

You must create a `.env` file in the root of the backend project subfolder with your [OpenAI API key](https://platform.openai.com/account/api-keys):

```
OPENAI_API_KEY=your_openai_api_key_here
```

### 3. Run the Components

Each subfolder contains a key piece of the system:

- `LOCAL_DEMO (try the model yourself!)`  
  → Run a local demo (you only need the analyzer.py, responder.py, and main.py files)

- `WEBSITE DEMO (frontend + backend)`  
  → Includes full frontend (React) and backend (Flask/FastAPI) code

- `AI_Emotional_Companion_code_for_report`  
  → Contains scripts used for evaluation and model analysis. Try exploring the about_user folder to discover the analysis of the model first-hand!

---

## 📂 Folder Structure

| Folder | Description |
|--------|-------------|
| `LOCAL_DEMO (try the model yourself!)` | Standalone local demo interface |
| `WEBSITE DEMO (frontend + backend)`   | Frontend (React) and backend (API) code |
| `AI_Emotional_Companion_code_for_report` | Model training, validation, and analysis |

---

## 📜 License

This project is for **academic and educational use only**.  
All rights reserved unless otherwise stated.

---

## 🏁 Final Note

The AI Emotional Companion is a small but significant step toward emotionally aware AI. It’s not a replacement for therapy—but it demonstrates that we can design AI systems that show care, listen deeply, and offer comfort.

Thanks again to my team and mentors who helped make this happen 🙏
