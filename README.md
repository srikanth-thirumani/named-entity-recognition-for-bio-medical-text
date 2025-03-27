# 🔬 BioMedText Analyzer

## Overview

BioMedText Analyzer is a powerful Flask-based web application designed to extract and visualize biomedical entities from various text sources, including PDFs, direct text input, and web URLs. This tool leverages Google's Gemini AI to provide advanced natural language processing for biomedical content.

## 🌟 Features

- **Multi-Source Text Analysis**
  - Upload PDF documents
  - Paste direct text input
  - Analyze content from web URLs

- **Advanced Entity Recognition**
  - Identifies key biomedical entities such as:
    * Diseases
    * Drugs
    * Genes
    * Proteins
    * Viruses
    * Chemicals
    * And more!

- **Detailed Insights**
  - Entity highlighting with color-coded visualization
  - Sentiment and context analysis
  - General insights generation

## 🛠 Technologies Used

- Flask
- Google Generative AI (Gemini)
- PyPDF2
- BeautifulSoup
- HTML/JavaScript for frontend
- Requests library for web scraping

## 📦 Prerequisites

- Python 3.8+
- Google Gemini API Key
- Flask
- Required Python packages (see `requirements.txt`)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/srikanth-thirumani/biomedtext-analyzer.git
cd biomedtext-analyzer
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up your Gemini API Key:
   - Replace `API_KEY` in the script with your actual Google Generative AI key

## 🖥 Running the Application

```bash
python app.py
```

Navigate to `http://localhost:5000` in your web browser.

## 🔐 Security Notes

- Always keep your API keys confidential
- Use environment variables for sensitive information
- Be cautious when analyzing web content from unknown sources

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Contact

Your Name - [srikanththirumani01@gmail.com]

Project Link: [https://github.com/srikanth-thirumani/biomedtext-analyzer](https://github.com/srikanth-thirumani/biomedtext-analyzer)

## 🙏 Acknowledgements

- Google Generative AI
- Flask Framework
- Open-source community
