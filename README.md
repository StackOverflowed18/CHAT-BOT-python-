# CHAT-BOT-python-
In this repo u"ll understand how we"ll make a chatbot for our college (tnp cell/ junior doubts regarding curriculumn)
## 📚 College Chatbot Project  

Welcome to the **College Chatbot** repository! 🚀 This project aims to build an interactive chatbot tailored for our college's **Training and Placement Cell (TNP)** and to assist juniors with **curriculum-related doubts**. 

This chatbot is designed to handle commonly asked queries about **placements**, **internships**, and general college life. For questions beyond its predefined responses, the chatbot leverages **OpenAI's GPT API** to provide intelligent and helpful replies.

---

## ✨ Features  

- **Quick Responses**: Handles frequently asked questions about TNP activities, such as placement drives and internships.  
- **Dynamic Replies**: Powered by OpenAI to answer non-predefined queries.  
- **User-Friendly Interface**: Interact with the chatbot via a clean and intuitive web interface.  
- **Customizable**: Add or update predefined questions and responses with ease.  

---

## 🛠️ Technologies Used  
     
- **Python**  
- **Flask** (for the backend and web interface)  
- **OpenAI GPT API** (for advanced conversational capabilities)  

---

## 🚀 How It Works  

1. **Predefined Responses**:  
   The chatbot first checks if the user's input matches any predefined questions. For example:  
   - **"hello" → "Hi there! How can I help you today?"**  
   - **"placements" → "The upcoming placement drives will be announced soon."**

2. **Dynamic AI Responses**:  
   If no predefined response is found, the chatbot uses the **OpenAI GPT API** to generate an intelligent response.  

3. **Web Interface**:  
   Users interact with the chatbot through a simple web page.  

---

## 🔧 How to Run the Project  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-username/college-chatbot.git  
   cd college-chatbot  
   ```


2. **Install Dependencies**:  
   Make sure you have Python installed. Then, install the required libraries:  
   ```bash  
   pip install flask openai  
   ```

3. **Set Your OpenAI API Key**:  
   Replace `openai.api_key` in the code with your own API key.  
   > ⚠️ **Note**: Keep your API key secure and private. Avoid exposing it in public repositories.  

4. **Run the Application**:  
   ```bash  
   python app.py  
   ```  

5. **Access the Web Interface**:  
   Open your browser and go to `http://127.0.0.1:5000/` to chat with the bot.  

---

## 📋 Predefined Questions  

Here are some predefined questions your bot can answer right away:  

| **User Input** | **Bot Response** |  
|----------------|------------------|  
| `hello`        | "Hi there! How can I help you today?" |  
| `placements`   | "The upcoming placement drives will be announced soon." |  
| `internships`  | "For internship opportunities, please visit the internships section on the TNP portal." |  

Feel free to expand this list in the `qa_pairs` dictionary to handle more queries.

---
##📎 File Structure  
```
college-chatbot/  
│  
├── templates/  
│   └── index.html   # HTML template for the web interface  
├── app.py           # Main Flask application  
├── requirements.txt # List of dependencies  
└── README.md        # Project documentation (this file)  
```
---
🙌 Contributions  
<a href="https://github.com/brobrocoder48">brobrocoder48</a>
---
 📧 Contact  
For any questions or suggestions, feel free to reach out to the project maintainer at anshimasinghask@gmail.com (stackoverflowed18) or ekanshjain2510@gmail.com (brobrocoder48)  
---  


