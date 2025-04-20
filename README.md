# AI-Based Adaptive Tutor with Condition Memory

Welcome to **AI-Based Adaptive Tutor with Condition Memory**, a capstone project that redefines the way students learn math! This interactive tutor guides learners through algebraic problems step-by-step using AI-generated hints, dynamic adaptation, and memory of student performance.

---

## 🎯 Project Goal
To create an **AI-powered adaptive math tutor** that:
- Never provides full solutions
- Offers targeted hints and guiding questions
- Analyzes student responses to determine correctness
- Adapts its strategy based on previous interactions (condition memory)

---

## 🚀 Demo
![Demo GIF or Screenshot Placeholder](link-to-your-demo.gif)

---

## 🔍 Key Features

- 🤖 Powered by **Groq’s Qwen model** for fast, intelligent hint generation
- 🧠 Adaptive system prompt generation using LangChain
- ✅ Student response classification: `correct`, `partially_correct`, `incorrect`
- 📚 Condition memory: modifies hints based on consecutive incorrect attempts
- 💬 Hint-level reasoning and expandable explanations
- 🧩 JSON-based structured tutor responses for reliability

---

## 📦 Tech Stack
| Technology         | Purpose                                      |
|--------------------|----------------------------------------------|
| Streamlit          | User interface                               |
| LangChain          | Prompt management, chaining, memory          |
| Groq + Qwen Model  | High-speed LLM for hints and analysis        |
| Python + Pydantic  | Output validation and structured responses   |
| dotenv             | Environment variable management              |

---

## 📁 File Structure
```
📦 Ai-based-Adaptive-Tutor-with-Condition-Memory
 ┣ 📄 int-tut.py                  # Main application logic
 ┣ 📄 requirements.txt            # Dependencies
 ┣ 📄 .env.example                # Environment variable example
 ┣ 📄 README.md                   # This file
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/MDalamin5/Ai-based-Adaptive-Tutor-with-Condition-Memory.git
cd Ai-based-Adaptive-Tutor-with-Condition-Memory
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables
Create a `.env` file in the root folder and add your Groq API key:
```env
GROQ_API_KEY=your_groq_api_key_here
```

### 4. Run the Application
```bash
streamlit run int-tut.py
```

---

## 🧠 How It Works

1. **Student inputs a math problem or response**
2. **The AI tutor responds with a hint + guiding question**
3. **The system analyzes the student reply using sentiment classification**
4. **An adaptive system prompt is dynamically generated based on correctness**
5. **Consecutive incorrect responses trigger deeper hints and sub-step breakdowns**
6. **Tutor never provides full answers — only learning-driven guidance**

---

## 📊 Example Interaction
**Student:** Solve x² + 5x + 6 = 0  
**Tutor:** This is a quadratic equation. What method might help here? Can you try factoring it?

**Student:** (x+2)(x+3)  
**Tutor:** Great! That looks correct. Now what can we infer from this factored form?

---

## 🔐 Strict Tutor Policy
The tutor is designed to:
- ❌ Never solve more than one step at a time
- ❌ Never give direct answers
- ❌ Never proceed without student understanding
- ✅ Always provide hints, not solutions
- ✅ Always ask guiding questions

---

## 🙌 Credits
**Al-Amin** – Final Year CSE Student at North South University 
This is part of my capstone project focused on building intelligent educational tools using generative AI.

---

## 📃 License
This project is open-sourced under the MIT License.

---

## 🌟 Star the Repo
If you find this project helpful, consider giving it a ⭐ on [GitHub](https://github.com/MDalamin5/Ai-based-Adaptive-Tutor-with-Condition-Memory)!

