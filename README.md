# Moodify - AI-Powered Mental Health Support Chatbot

## 🌟 Overview
Moodify is an AI-driven mental health support chatbot that provides real-time sentiment analysis and personalized responses to user inputs. Using state-of-the-art NLP techniques and the Llama-3.3-70B-Instruct-Turbo model, Moodify aims to offer emotional support and coping strategies while ensuring user privacy.

## 🚀 Features
- **Sentiment Analysis**: Analyzes user input to determine emotional tone.
- **AI-Powered Responses**: Generates supportive and meaningful responses using Llama-3.3-70B-Instruct-Turbo.
- **Mood Tracking**: Logs and visualizes user sentiment trends over time.
- **Coping Strategies**: Provides context-aware mental health support suggestions.
- **Privacy-Focused**: Ensures no permanent data storage for user interactions.

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **NLP & AI**: TensorFlow, OpenAI GPT-3.5, BERT, TextBlob
- **Backend**: Python, FastAPI (optional for deployment)
- **Data Handling**: Pandas, NumPy
- **API Integration**: DeepInfra API for AI-generated responses

## 🔧 Installation
### Prerequisites
- Python 3.8+
- Virtual environment (optional but recommended)

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/moodify.git
   cd moodify
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set up API key for DeepInfra (replace `your_deepinfra_api_key` in `app.py`):
   ```python
   DEEPINFRA_API_KEY = "your_deepinfra_api_key"
   ```

## ▶️ Running the Application
Start the chatbot by running:
```sh
streamlit run app.py
```

## 📊 How It Works
1. **User Input**: The user types a message in the chatbot.
2. **Sentiment Analysis**: The app analyzes the sentiment using TextBlob.
3. **AI Response**: A context-aware response is generated using Llama-3.3-70B.
4. **Mood Tracking**: Sentiments are logged and visualized for users.
5. **Coping Strategies**: The app suggests strategies based on detected sentiment.

## 📌 Screenshots
(Include relevant UI screenshots here)

## 🤝 Contributing
We welcome contributions! Feel free to fork the repo and submit a pull request.

## 📜 License
MIT License. See `LICENSE` for more details.

## 📬 Contact
For questions or suggestions, reach out at [your-email@example.com](mailto:your-email@example.com).

