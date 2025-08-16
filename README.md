# Resume_Screener

📌 Project Overview
The Resume Screener project is an NLP-based application designed to automatically rank resumes based on extracted information using Named Entity Recognition (NER). By leveraging SpaCy and advanced text processing, the model identifies key skills, experience, and qualifications from resumes and ranks them to aid in candidate selection.
📂 Dataset
We use a Resume Dataset containing various resumes in text/PDF format. The dataset includes resumes from multiple domains, ensuring diversity in skills and qualifications for training and evaluation.
🛠️ Skills & Libraries
- Natural Language Processing (NLP)
- SpaCy for Named Entity Recognition (NER)
- Text Preprocessing (tokenization, stopword removal, lemmatization)
- Ranking Algorithms for scoring resumes
- Python libraries: pandas, numpy, scikit-learn
✨ Features
- Extracts key information such as skills, education, and experience from resumes
- Uses NER (Named Entity Recognition) for precise entity detection
- Ranks resumes based on defined criteria (skills match, years of experience, etc.)
- Can be extended to include job description matching
- Supports text/PDF formats
⚙️ How It Works
1. Load and preprocess resumes from the dataset
2. Apply SpaCy’s NER model to extract key entities
3. Score resumes based on entity matches with desired criteria
4. Rank resumes from most relevant to least relevant
5. Output top-ranked candidates
💻 Installation
1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Place resumes inside the `data/resumes/` folder
4. Run `python main.py` to start screening
📊 Visualization
The results can be visualized using bar charts or tables showing the ranking of resumes. Additional insights like top skills matched and candidate score distributions can also be generated.


✅ Conclusion
The Resume Screener simplifies candidate shortlisting by automating the tedious process of reading and ranking resumes. It can be further enhanced by integrating job descriptions and fine-tuned NER models.
