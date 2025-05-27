# 🎓 CollegeBot – AI Assistant for Indian College Admissions (Post Class 12th)

CollegeBot is a smart and student-friendly AI chatbot that assists with **college admission guidance in India**.  
Built using [**Groq**](https://groq.com/) (powered by LLaMA 3) and [**Gradio**](https://www.gradio.app/), this tool helps students find relevant information about colleges, courses, ranks, fees, entrance exams, and more — all through natural conversation.

---

## 🚀 Features

🎓 AI-powered admission assistant focused on Indian colleges  
📊 Helps with courses, cutoffs, fees, NIRF rankings, hostel info, placements, etc.  
💬 Simple and interactive chat interface via [Gradio](https://www.gradio.app/)  
⚡ Powered by [Groq](https://console.groq.com/)’s ultra-fast inference engine  
🛠️ Easily extendable to add live data or APIs

---

## 🛠️ Installation

Install required dependencies:

```bash
pip install groq
pip install gradio
````

---

## 🧠 How to Use

1. Sign up at [https://console.groq.com/](https://console.groq.com/) and get your API key.
2. Replace the API key placeholder in the script:

```python
client = Groq(api_key="your_groq_api_key_here")
```

3. Run the Python script to launch the chatbot:

```bash
python app.py
```

4. Start chatting! Example queries:

* `"Cutoff for B.Tech in IIT Bombay"`
* `"Best private colleges for BBA"`
* `"Fees of AIIMS Delhi"`
* `"Scope of BA Psychology"`
* `"Do I need NEET for BPT?"`

---

## 🔧 Tech Stack

* [**Python**](https://www.python.org/) 3.11+
* [**Groq API**](https://console.groq.com/) – For AI chat completions (LLaMA 3 model)
* [**Gradio**](https://www.gradio.app/) – UI framework for chat interface
* Optional: [**Hugging Face Spaces**](https://huggingface.co/spaces) or [**Google Colab**](https://colab.research.google.com/) for deployment

---

## 🧾 Example Queries

* `"Best engineering colleges accepting JEE Main score"`
* `"Cutoff rank for CSE in NIT Trichy"`
* `"Top medical colleges with hostel facilities"`
* `"Is SRM University private or government?"`
* `"Fees and placements for BITS Pilani"`

---

## 📂 Folder Structure

```
CollegeBot/
│
├── app.py                # Main script to run the chatbot
├── README.md             # Project overview
├── requirements.txt      # Python dependencies (optional)
└── screenshot.png        # Interface preview (optional)
```

---

## 💡 Future Enhancements

* 🔄 Integrate real-time rank cut-off and college database via API
* 📊 Visualize comparison between colleges
* 📱 Add mobile-friendly voice input/output
* 🌍 Support for regional languages (Hindi, Malayalam, etc.)
* 📆 Add alerts for admission deadlines and entrance exams

---

## 🙌 Acknowledgements

* [**Groq**](https://groq.com/) – For the ultra-fast and intelligent LLaMA 3 inference engine
* [**Gradio**](https://www.gradio.app/) – For the simple and powerful chatbot UI
* **NIRF**, **JoSAA**, **CUET**, etc. – For data references
* **Google Colab / Hugging Face Spaces** – For hosting and testing support

---

## 📜 License

This project is licensed under the **MIT License** – free for personal and educational use.

