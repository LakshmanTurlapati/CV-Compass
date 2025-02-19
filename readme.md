


# CV Compass

CV Compass is a Python-based tool that matches resumes with job descriptions using TF-IDF and cosine similarity. It extracts text from various file formats and ranks resumes based on their relevance to a given job description.

## Features
- Supports **PDF, DOCX, TXT, XLS, XLSX, PPT, PPTX** resume formats.
- Uses **TF-IDF Vectorization** to analyze resume content.
- Caches processed data for efficiency.
- Provides key term analysis for top-matching resumes.

## Installation

1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   
2. Create necessary directories:
   ```sh
   mkdir resumes job_descriptions .cache
   ```

## Usage

1. Add resumes to the `resumes/` directory.
2. Add job descriptions as JSON files in `job_descriptions/`.
3. Run the script to find the best-matching resume:
   ```sh
   python cv_compass.py
   ```

## Job Description Format

Each job description should be a JSON file in the following format:

```json
{
  "title": "Software Engineer",
  "description": "Develop and maintain software solutions...",
  "requirements": "Experience in Python, Java, and cloud services..."
}
```

## Output

The script will display the best-matching resume along with key terms that influenced the match.



