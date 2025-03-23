🧠 Flask Chatbot with Microsoft Phi-3 Mini

This project is a simple chatbot built with Flask and Microsoft Phi-3 Mini, leveraging Hugging Face Transformers to handle natural language processing.



📑 Table of Contents

Installation

Usage

API Endpoint

Technologies Used

Future Improvements

Contributing

License



⚙️ Installation

Clone the repository:

git clone https://github.com/Nonny-123/FLASK-API-Chatbot.git
cd FLASK-API-Chatbot

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt



🚀 Usage

Run the Flask app:

python flask_chatbot_app.py

Access the app:
The app will run locally at:

http://localhost:5000



🔌 API Endpoint

URL: /chatbot

Method: POST

Request Body:

{
  "message": "Hello, chatbot!"
}

Response:

{
  "response": "Hi there! How can I help you today?"
}



🏗️ Technologies Used

Python 🐍

Flask 🌐

Hugging Face Transformers 🤗

Microsoft Phi-3 Mini 🧠



📌 Future Improvements

Implement conversation history management.

Add unit tests for API endpoints.

Integrate front-end UI for user interaction.




🤝 Contributing 

Contributions are welcome! Feel free to fork the repo, open issues, and submit a pull request.



📜 License

This project is licensed under the MIT License.


👨‍💻 Developed by Okonji Chukwunonyelim Gabriel.

