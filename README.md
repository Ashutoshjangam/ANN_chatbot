
# 🧠 AI Chatbot Web App using Flask

A simple and stylish chatbot web interface built using **Flask**, **HTML**, **CSS**, and **JavaScript**. This project demonstrates how to serve a chatbot that can return information (e.g., about Artificial Neural Networks) stored in a JSON file.

---

## 📌 Features

- Sleek and modern floating chatbox UI
- Responsive message handling between user and bot
- Answers based on a custom JSON knowledge base
- Easy to run locally using Python Flask

---

## 🖥️ Tech Stack

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, JavaScript
- **Knowledge Base:** JSON

---

## 📂 Project Structure

```
chatbot-app/
│
├── app.py                     # Flask server file
├── static/
│   ├── style.css              # CSS for styling chatbot
│   ├── app.js                 # JavaScript for client-side chat logic
│   └── images/
│       └── chatbox-icon.svg   # Optional chat icon (or you can add your own)
│
├── templates/
│   └── index.html             # Main webpage
│
├── data/
│   └── ann_knowledge.json     # Custom JSON knowledge base
│
├── README.md                  # You're reading it!
└── requirements.txt           # Python dependencies
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/chatbot-flask-app.git
cd chatbot-flask-app
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install the required Python packages

```bash
pip install -r requirements.txt
```

> If you don't have `requirements.txt`, you can manually install Flask:
```bash
pip install flask
```

### 4. Run the Flask app

```bash
python app.py
```

### 5. Open in browser

Visit `http://127.0.0.1:5000` in your browser. You'll see the chatbot floating in the bottom-right corner.

---

## 📚 How to Add Your Own Knowledge

Modify the `ann_knowledge.json` file inside the `data/` folder. It should follow this structure:

```json
{
  "What is ANN?": "Artificial Neural Networks (ANNs) are computing systems inspired by biological neural networks.",
  "Applications of ANN": "ANNs are used in image recognition, speech processing, and more."
}
```

You can update keys (questions) and values (answers) as needed.

---

## 🎨 Customize the UI

All styling is handled in `static/style.css`. You can:

- Change colors or gradients
- Adjust spacing
- Add animations or chat icon

---

## 💡 Ideas to Improve

- Connect to OpenAI/GPT or any AI model
- Add authentication or user session memory
- Store chat history in a database
- Add voice input/output

---

## 📃 License

This project is open-source and free to use under the [MIT License](LICENSE).
