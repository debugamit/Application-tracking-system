# Application tracking system 
 ATS system using google gemini pro vision 
 Here’s a well-organized `README.md` file for your **Project Application Tracking System (ATS)**:

---

# ATS Resume Expert - Project Application Tracking System

This repository provides an **ATS Resume Expert** tool for evaluating resumes against job descriptions using **Google Gemini Pro Vision**. The system uses advanced generative AI to assess resume-job description alignment, highlighting strengths, weaknesses, and areas for improvement.

## Features
- **Resume Analysis**: Leverages **Gemini Pro Vision** to evaluate resumes against job descriptions.
- **Match Percentage**: Calculates the match percentage and provides insights into missing keywords.
- **Strengths and Weaknesses**: Offers detailed feedback on candidate suitability for a job role.

---

## Installation

### Prerequisites
- Python 3.7 or higher
- Install required libraries listed in `requirements.txt`.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ats-resume-expert.git
   cd ats-resume-expert
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up your environment:
   - Create a `.env` file in the project root and add your **Google Gemini API Key**:
     ```env
     GOOGLE_API_KEY=your-google-api-key
     ```
5. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. **Input Job Description**: Add the job description in the text area provided.
2. **Upload Resume**: Upload your resume in PDF format.
3. **Analysis**:
   - **Professional Evaluation**: Click **Tell Me About the Resume** to get strengths and weaknesses.
   - **Percentage Match**: Click **Percentage Match** to see alignment percentage and improvement suggestions.

---

## File Structure
```plaintext
.
├── app.py                  # Main Streamlit application
├── requirements.txt        # List of required libraries
├── README.md               # Project documentation
├── .env                    # Environment variables (not included in repo)
```

---

## Requirements
Below are the key dependencies for the project:
- `streamlit`
- `google-generativeai`
- `python-dotenv`
- `pdf2image`

Install them using:
```bash
pip install -r requirements.txt
```

---

## How It Works

1. **PDF Handling**: Converts uploaded PDF resumes to image format for processing.
2. **Gemini Pro Vision**:
   - Uses `google.generativeai` to analyze the resume and job description.
   - Generates content based on the prompts provided.
3. **Prompts**:
   - Professional Evaluation: Analyzes resume strengths and weaknesses.
   - ATS Match: Provides a match percentage and lists missing keywords.

---

## Demo

![Demo Screenshot](https://via.placeholder.com/800x400?text=Add+Screenshot+Here)

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---

## Author
- **Your Name**: [Your LinkedIn](https://www.linkedin.com/) | [Your Portfolio](https://your-portfolio.com)

---

Let me know if you’d like assistance adding visuals or further refining this!
