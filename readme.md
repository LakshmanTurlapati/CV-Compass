# CV Compass 🎯

*Because finding the perfect resume-job match shouldn't feel like finding a needle in a haystack!* 😉

Welcome to **CV Compass**, your AI-powered sidekick for intelligent resume matching. This Python-based tool uses advanced NLP techniques to match resumes with job descriptions, making the recruitment process smarter and more efficient.

## 🌟 Features

- **Multi-Format Support:** Handles virtually any resume format you throw at it:
  - 📄 PDF documents
  - 📝 Word documents (DOCX)
  - 📊 Excel spreadsheets (XLS/XLSX)
  - 📑 PowerPoint presentations (PPT/PPTX)
  - ✍️ Plain text files (TXT)

- **Smart Matching Engine:** 
  - Uses TF-IDF Vectorization to understand document context
  - Employs Cosine Similarity for accurate matching
  - Identifies key terms that influenced the match
  
- **Performance Optimized:**
  - Smart caching system for processed documents
  - Efficient document processing pipeline
  - Quick results even with large resume collections

## 🚀 Quick Start

1. **Set Up Your Environment:**
   ```bash
   # Create and activate virtual environment
   python3 -m venv venv
   source venv/bin/activate

   # Install dependencies
   python3 -m pip install -r requirements.txt
   ```

2. **Prepare Your Workspace:**
   ```bash
   mkdir resumes job_descriptions .cache
   ```

3. **Add Your Documents:**
   - Place resumes in the `resumes/` directory
   - Add job descriptions to `job_descriptions/`

4. **Run the Magic:**
   ```bash
   python3 cv_compass.py
   ```

## 📋 Job Description Format

Create your job descriptions as JSON files with this structure:

```json
{
  "title": "Senior Python Developer",
  "description": "Looking for an experienced developer...",
  "requirements": "5+ years Python, REST APIs, Cloud platforms..."
}
```

## 🛠️ How It Works

Peek under the hood of our matching engine:

1. **Document Processing:**
   - Extracts text from various file formats
   - Preprocesses content for optimal analysis
   - Builds a searchable document index

2. **TF-IDF Magic:**
   - Converts documents into numerical vectors
   - Identifies important terms and patterns
   - Creates a mathematical representation of content

3. **Smart Matching:**
   - Calculates similarity scores
   - Ranks resumes by relevance
   - Highlights matching terms and skills

## 🤝 Contributing

Let's make CV Compass even better! Here's how you can help:

1. **Fork the Repository**
2. **Create a Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit Your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

## 🎯 Future Enhancements

- [ ] Add support for more file formats
- [ ] Implement machine learning-based matching
- [ ] Create a web interface
- [ ] Add batch processing capabilities
- [ ] Integrate with ATS systems

## About the Project

Created with ❤️ by [Lakshman Turlapati](https://github.com/LakshmanTurlapati)

---

*May your perfect candidate be just one match away!* ✨



