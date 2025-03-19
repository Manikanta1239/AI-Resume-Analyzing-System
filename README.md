# AI Resume Analyzing System

A powerful web application that uses AI to analyze resumes against job descriptions, providing detailed evaluations and match percentages. Built with Streamlit and powered by Google's Gemini 1.5 Flash AI.

## 🚀 Features

- **Resume Analysis**: Get detailed professional evaluations of your resume from an HR perspective
- **ATS Scanning**: Calculate match percentage against job descriptions
- **Keyword Analysis**: Identify missing keywords and improvement areas
- **User-Friendly Interface**: Clean and intuitive design with animations and real-time feedback
- **PDF Support**: Handles PDF resume uploads with image conversion capabilities

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
base64
google-generativeai
pdf2image
Pillow
python-dotenv
streamlit
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
   - 🔎 Analyze Resume: For detailed HR evaluation perspective
   - 📈 PERCENTAGE Match: For ATS matching score and missing keywords

## 💡 How It Works

The system uses Google's Gemini 1.5 Flash AI to:
1. Convert PDF resumes to images for processing
2. Analyze resumes for various job roles including:
   - Data Science
   - Data Analyst
   - DevOPS
   - Machine Learning Engineer
   - Prompt Engineer
   - AI Engineer
   - Full Stack Web Development
   - Big Data Engineering
   - Marketing Analyst
   - Human Resource Manager
   - Software Developer
3. Provide detailed analysis from an HR perspective
4. Calculate ATS matching scores and identify missing keywords

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Manikanta Yadav**
- Email: smanikanta1239@gmail.com
- LinkedIn: [mani-kanta-092202268](https://www.linkedin.com/in/mani-kanta-092202268/)

