# AI-Based Resume Screening and Parsing System

## Overview

This project demonstrates an AI-assisted resume screening system that simulates how modern Applicant Tracking Systems (ATS) analyze and rank candidates.

The system processes unstructured resume text, extracts key information, and evaluates candidates against a defined job description using both keyword-based filtering and machine learning techniques.

This project is designed to showcase practical applications of AI in Human Resource Management (HRM), particularly in recruitment automation.

---

## Key Features

* Unstructured resume text processing
* Resume parsing using pattern matching (Regex)
* Extraction of candidate attributes:

  * Skills
  * Experience
  * Education
  * Certifications
* ATS-style keyword matching
* TF-IDF vectorization for text representation
* Cosine similarity for resume-job matching
* Candidate scoring and ranking system
* Recommendation classification (Strong Fit, Moderate Fit, Low Fit)
* Export of final results for business tools (Excel / Power BI)

---

## Technologies Used

* Python
* Pandas
* Regular Expressions (re)
* Scikit-learn

  * TfidfVectorizer
  * Cosine Similarity

---

## Workflow

1. Synthetic resume dataset creation (20 candidates)
2. Resume parsing from unstructured text
3. Feature extraction:

   * Skills
   * Experience
   * Education
   * Certifications
4. Job description definition
5. Keyword matching (ATS simulation)
6. TF-IDF vectorization
7. Similarity computation using cosine similarity
8. Feature normalization
9. Weighted scoring model
10. Candidate ranking and recommendation generation

---

## Scoring Model

The final candidate score is calculated using a weighted approach:

* Keyword Match Score: 30%
* Text Similarity Score: 30%
* Experience Score: 20%
* Education Score: 10%
* Certification Score: 10%

This ensures a balanced evaluation of both textual relevance and candidate qualifications.

---

## Output

The system generates a structured dataset with the following fields:

* Candidate ID
* Resume Text
* Extracted Skills
* Experience (Years)
* Education
* Certifications
* Keyword Match Count
* Similarity Score
* Final Score
* Recommendation Label

The output is exported as:

resume_parsing_screening_output.csv

---

## Business Use Case

This project simulates how organizations:

* Automate resume screening at scale
* Reduce manual effort in shortlisting candidates
* Improve hiring efficiency using AI-assisted tools
* Support HR decision-making with data-driven insights

---

## Limitations

* Rule-based parsing may not handle complex resume formats
* Keyword matching lacks deep contextual understanding
* Synthetic dataset does not represent real-world variability
* Model does not address bias or fairness issues

---

## Future Enhancements

* Integration with real resume datasets (PDF/DOC parsing)
* Use of NLP libraries (SpaCy, Transformers)
* Named Entity Recognition (NER) for advanced parsing
* Deep learning-based resume matching models
* Bias detection and fairness-aware scoring
* Deployment as a web-based HR analytics tool

---

## Conclusion

This project highlights how AI can assist in resume screening and candidate ranking. While automation improves efficiency, human judgment remains essential for final hiring decisions.

---

## Author

Preeti
AI & Data Analytics Student
Focused on AI in HR, Analytics, and Business Intelligence

