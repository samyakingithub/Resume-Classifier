# Resume Classifier

This project leverages machine learning to classify resumes into specific categories, streamlining the recruitment process for organizations. By analyzing resume content with advanced NLP techniques and various machine learning algorithms, it efficiently identifies the most suitable classification.

---

## Overview

The **Resume Classifier** project simplifies the recruitment process by categorizing resumes into fields like software development, data science, and management. It uses:

1. **Dataset Loading**: Reads and preprocesses resume data from CSV files.
2. **Data Exploration**: Identifies unique categories for classification.
3. **Model Training**: Employs multiple machine learning algorithms, including SVM, KNN, and Random Forest, to build and evaluate classifiers.
4. **Classification**: Classifies resumes into predefined categories based on their content.

---

## Features
- Automated classification of resumes into predefined categories.
- Utilization of NLP for resume content analysis.
- High accuracy and scalable for large datasets.
- Easy integration with recruitment systems.

---

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip (Python package manager)
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/resume-classifier.git
   cd resume-classifier
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the dataset (`UpdatedResumeDataSet.csv`) in the `data/` directory.

---

## Usage

### Running the Project
1. Preprocess the data:
   ```bash
   python preprocess_data.py
   ```
2. Train the model:
   ```bash
   python train_model.py
   ```
3. Classify new resumes:
   ```bash
   python classify_resumes.py --input resumes/sample_resume.pdf
   ```

### Example Command
To classify resumes in a folder:
```bash
python classify_resumes.py --input_folder resumes/
```

---

## Technologies Used
- **Programming Languages:** Python
- **Libraries:**
  - Natural Language Processing: NLTK, spaCy
  - Machine Learning: scikit-learn
  - Data Processing: pandas, NumPy
  - Visualization: matplotlib

---

## Results
- **Accuracy:** Achieved over 90% classification accuracy on test data.
- **Key Insights:** Robust preprocessing enhances classification performance.

---

## Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements
- Dataset source: `UpdatedResumeDataSet.csv`
- Libraries and tools: scikit-learn, pandas, NLTK
- Special thanks to open-source contributors and the machine learning community.

---
