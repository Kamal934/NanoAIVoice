# 🎙️ NanoAiVoice

NanoAiVoice is a simple and intuitive voice assistant developed using Python. It leverages OpenAI's GPT-3 API for language understanding and response generation, SoundDevice for recording audio, and pyttsx3 for text-to-speech conversion.

## 🌟 Features

- **🎤 Voice Recognition:** Listens to user's voice commands and transcribes them to text.
- **🧠 AI Conversation:** Communicates with users in natural language using OpenAI's GPT-3 model.
- **🗣️ Text-to-Speech:** Converts the assistant's text responses into voice and speaks them out.

## 🛠️ Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Kamal934/NanoAIVoice.git
    cd NANOAIVOICE
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Create a `.env` file in the root directory and add your OpenAI API key:**

    ```text
    OPENAI_API_KEY=your_openai_api_key_here
    ```

## 🚀 Usage

**Run the voice assistant:**

    python nanoaivoice.py

   **Interact with the assistant:** Speak to the assistant when prompted. To exit, say "goodbye".

## 📁 Project Structure
    .
    ├── .env
    ├── README.md
    ├── nanoaivoice.py
    ├── requirements.txt
    ├── LICENSE
    └── .gitignore


## 💡 Example

 Here's a brief example of how the assistant works:
-  The assistant listens for your voice command.
-  It transcribes the audio to text using OpenAI's Whisper model.
-  It generates a response using GPT-3.
-  It converts the response text to speech and speaks it out.

## 🤝 Contributing

Contributions are welcome! Please create an issue or submit a pull request for any features, bug fixes, or improvements.

## 📜 License

This project is licensed under the Apache License. See the [LICENSE](http://www.apache.org/licenses/LICENSE-2.0) file for details.

---

**Note:** This project is for educational purposes only. Use at your own risk.
