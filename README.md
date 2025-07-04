
markdown
# 🤖 Gemini Pro - ChatBot

Welcome to **Gemini Pro**, a conversational AI chatbot built using **Streamlit** and powered by Google's **Gemini-Pro** large language model. This project allows users to interact with the Gemini API via a sleek and responsive web interface.

## 🚀 Features

- Chat interface powered by Streamlit
- Real-time interactions with the Gemini-Pro LLM
- Styled with emojis and layout configurations
- Environment-secured API key management via `dotenv`



## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/gemini-pro-chatbot.git
   cd gemini-pro-chatbot
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your `.env` file**
   Create a `.env` file in the root directory and add your Gemini API key:
   ```
   GOOGLE_API_KEY=your_google_api_key_here
   ```

4. **Run the app**
   ```bash
   streamlit run main.py
   ```

## 🧠 How It Works

- The app uses `google.generativeai` to interface with Gemini.
- User input is captured via `st.chat_input` and sent to the model.
- Past messages are stored in `st.session_state` to preserve conversation history.
- Responses from the model are displayed using `st.chat_message`.

## 📷 Screenshot

Coming soon! (You can add a screenshot of your running app here.)

## 📌 To Do

- Add error handling for invalid API keys
- Implement session saving/loading
- Style improvements and theming

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 📄 License

MIT License – feel free to use and adapt this project as needed.





