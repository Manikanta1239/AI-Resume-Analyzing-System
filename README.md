# AI Resume Analyzing System

A powerful web application that uses AI to analyze resumes against job descriptions, providing detailed evaluations and match percentages. Built with Streamlit and powered by Google's Gemini AI.


## 🚀 Features

- **Resume Analysis**: Get detailed professional evaluations of your resume
- **ATS Scanning**: Calculate match percentage against job descriptions
- **Keyword Analysis**: Identify missing keywords and improvement areas
- **User-Friendly Interface**: Clean and intuitive design with real-time feedback
- **PDF Support**: Handles PDF resume uploads seamlessly

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AI-Resume-Analyzing-System.git
cd AI-Resume-Analyzing-System
```

2. Create a virtual environment:
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the project root and add your Google API key:
```plaintext
GOOGLE_API_KEY=your_api_key_here
```

## 📋 Requirements

```plaintext
streamlit==1.31.0
pdf2image==1.16.3
google-generativeai==0.3.0
python-dotenv==1.0.0
Pillow==10.2.0
```

## 🚀 Usage

1. Start the application:
```bash
streamlit run app.py
```

2. Open your browser and navigate to `http://localhost:8501`

3. Upload your resume (PDF format)

4. Paste the job description

5. Choose between:
   - 🔎 Analyze Resume: For detailed evaluation
   - 📈 PERCENTAGE Match: For ATS matching score

## 💡 How It Works

The system uses Google's Gemini AI to:
1. Extract information from uploaded resumes
2. Compare resume content with job descriptions
3. Provide detailed analysis and recommendations
4. Calculate matching scores based on ATS criteria

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Manikanta Yadav**
- Email: smanikanta1239@gmail.com
- LinkedIn: [mani-kanta-092202268](https://www.linkedin.com/in/mani-kanta-092202268/)

