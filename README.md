# Scam & URL Detector Web App

A Flask-based web application that uses Google Gemini AI to detect scam or phishing content in emails, PDFs, text files, and URLs. This project demonstrates AI integration, web development, and cybersecurity awareness.

# Features

✅ Detect whether an email, PDF, or text file contains real or scam content.

✅ Classify URLs into:

benign – safe websites

phishing – fraudulent websites

malware – websites distributing malicious software

defacement – hacked or altered websites

✅ Upload files in PDF or TXT format for analysis.

✅ Simple and intuitive web interface using Flask.

✅ Powered by Google Gemini AI for accurate content classification.

# Demo Screenshot

<img width="780" height="308" alt="image" src="https://github.com/user-attachments/assets/7c9eba06-e2c5-4d9f-a2ca-14ed4752dff1" />

<img width="950" height="470" alt="image" src="https://github.com/user-attachments/assets/8c078071-04d3-46f5-b585-64404b6ef349" />


# Installation

# Clone the repository:

git clone https://github.com/your-username/scam-url-detector.git
cd scam-url-detector


# Create a virtual environment (recommended):

python -m venv venv
source venv/bin/activate  # Linux / Mac
venv\Scripts\activate     # Windows


# Install dependencies:

pip install -r requirements.txt


# Set up Google API Key:

Create a .env file in the project root:

GOOGLE_API_KEY=your_google_gemini_api_key

# Usage

# Run the Flask app:

python app.py


# Open your browser and go to:

http://127.0.0.1:5000/


# Detect scam emails:

Upload a PDF or TXT file.

Click “Analyze”.

# Detect malicious URLs:

Enter a URL in the form.

Click “Predict”.

File Upload Supported Formats

.pdf – PDF files

.txt – Text files

# Technologies Used

Python – Core programming language

Flask – Web framework

PyPDF2 – PDF text extraction

Google Gemini AI – AI-powered text & URL classification

HTML/CSS – Frontend design

# Project Structure
scam-url-detector/
│
├── app.py              # Main Flask app
├── templates/
│   └── index.html      # Web interface
├── static/             # Optional: CSS/JS files
├── requirements.txt    # Dependencies
└── README.md           # Project documentation

# Security Notice

Do not hardcode your Google API key in the code. Always use environment variables.

This project is for educational and demo purposes only. Always verify URLs and emails with proper tools in production.

# Contributing

Contributions are welcome! Feel free to:

Improve UI design

Add more file types (e.g., DOCX)

Add logging or history for predictions

License

MIT License – feel free to use and modify this project.
