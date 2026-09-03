# AI Personal Assistant

A simple AI-based personal assistant built using Python and Flask.
It uses the Groq API to generate responses and summarize emails.

## Features

* Ask questions and get AI-generated responses
* Summarize long emails into short summaries
* REST API integration using Flask
* Secure API key management using `.env`
* Markdown formatted responses
* Responsive web interface
* Loading and error handling

## Tech Stack

* Python
* Flask
* Groq API
* LLM
* HTML
* CSS
* JavaScript

## Project Structure

```text
AI-Personal-Assistant-Flask/
│
├── main.py
├── .gitignore
├── README.md
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## How to Run

1. Clone the repository.
2. Install the required packages.
3. Create a `.env` file.
4. Add your Groq API key.
5. Run the Flask application.

Install dependencies:

```bash
pip install flask groq python-dotenv
```

Run the application:

```bash
python main.py
```

Then open the application in your browser:

```text
http://127.0.0.1:5000
```

## Environment Variable

Create a `.env` file in the project folder:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Do not upload the `.env` file to GitHub.

## Future Improvements

* Add chat history
* Add voice input
* Add more AI features
* Deploy the application online
