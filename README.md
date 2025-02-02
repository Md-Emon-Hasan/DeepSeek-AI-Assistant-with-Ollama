# 🧠 Custom DeepSeek Assistant for Programming
![Image](https://github.com/user-attachments/assets/53054efa-e8a8-4c31-9b5b-b8a75555c2ac)

A powerful AI-powered coding assistant built using **DeepSeek AI**, **LangChain**, and **Ollama**. This assistant can help with Python programming, code debugging, documentation, and solution design.

---

## 🚀 Features

- 🐍 **Python Expert:** Provides accurate code solutions.
- 🐞 **Debugging Assistant:** Identifies and resolves bugs with strategic print statements.
- 📝 **Code Documentation:** Generates professional code documentation.
- 💡 **Solution Design:** Assists in designing efficient coding solutions.

---

## ⚙️ Technologies Used

- **[Streamlit](https://streamlit.io/):** For creating the web interface.
- **[LangChain](https://python.langchain.com/):** Manages LLM prompts and workflows.
- **[Ollama](https://ollama.ai/):** Runs DeepSeek models locally.
- **DeepSeek AI Models:** `deepseek-r1:1.5b` and `deepseek-r1:3b`.

---

## 🗂️ Project Structure

```
├── app.py                # Main Streamlit application
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

---

## 🛠️ Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/custom-deepseek-assistant.git
   cd custom-deepseek-assistant
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/macOS
   venv\Scripts\activate      # For Windows
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Ollama Locally:**  
   Make sure Ollama is running on `http://localhost:11434`.

5. **Start the Application:**
   ```bash
   streamlit run app.py
   ```

---

## ⚡ How It Works

1. Select the **DeepSeek model** (`1.5b` or `3b`) from the sidebar.
2. Enter your coding question in the chat input field.
3. The assistant responds with code suggestions, debugging tips, and more.

---


## 🙋‍♂️ Developer Info

- **Customized by:** Md Emon Hasan  
- **GitHub:** [Md-Emon-Hasan](https://github.com/Md-Emon-Hasan)  
- **LinkedIn:** [Md Emon Hasan](https://www.linkedin.com/in/md-emon-hasan)  
- **Email:** [iconicemon01@gmail.com](mailto:iconicemon01@gmail.com)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## ⭐ Show Your Support

If you found this project helpful:
- Give it a ⭐ on GitHub
- Share it with your friends
- Fork and contribute to the project 🚀
