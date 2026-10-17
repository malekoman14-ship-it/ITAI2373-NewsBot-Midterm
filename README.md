# ITAI2373-NewsBot-Midterm
# NewsBot Intelligence System

**Course:** ITAI 2373 – Natural Language Processing  
**Project:** Midterm Project  
**Group Members:** Oman Malek, Tobias Chow, Cris Williams, Mahdi Mohammadkhani 
**Platform:** Google Colab  
**Programming Language:** Python

## 1. Project Overview

The NewsBot Intelligence System is a Natural Language Processing (NLP) project designed to automatically analyze, organize, and classify news articles.

The project integrates eight NLP modules to demonstrate how unstructured text can be transformed into meaningful information. It includes text preprocessing, feature extraction, grammatical analysis, sentiment analysis, machine learning classification, and named entity recognition.

The main objective is to develop an end-to-end NLP workflow that can help users understand and organize large collections of news articles.

## 2. Dataset Information

**Dataset:** BBC News Classification  
**Source:** [Kaggle – BBC News Classification](https://www.kaggle.com/competitions/learn-ai-bbc/data)  
**Dataset File:** `BBC News Train.csv`  
**Total Articles:** 1,490  
**Number of Categories:** 5  
**Dataset Status:** Approved by the course instructor

The five news categories are:

- Business
- Entertainment
- Politics
- Sport
- Tech

The dataset contains English-language news articles with category labels. These articles are used for NLP analysis and machine learning classification.

## 3. Project Modules and Group Contributions

### Module 1 – Business Understanding and Dataset Exploration
**Responsible Member: Oman**

- Defined the purpose and business applications of NewsBot.
- Loaded and explored the BBC News dataset.
- Examined the article categories and their distribution.
- Checked data quality and prepared the dataset for analysis.

### Module 2 – Text Preprocessing
**Responsible Member: Oman**

- Converted text to lowercase.
- Removed unnecessary characters and stopwords.
- Applied tokenization and lemmatization.
- Prepared cleaned text for subsequent NLP tasks.

### Module 3 – TF-IDF Feature Extraction
**Responsible Member: Tobias**

- Converted text into numerical features using TF-IDF.
- Identified important terms within news articles.
- Explored how word importance differs across categories.

### Module 4 – Part-of-Speech Tagging
**Responsible Member: Tobias**

- Applied Part-of-Speech tagging to news text.
- Identified nouns, verbs, adjectives, and other grammatical categories.
- Explored grammatical patterns in news articles.

### Module 5 – Dependency Parsing
**Responsible Member: Cris**

- Analyzed grammatical relationships between words.
- Identified sentence structure and dependencies.
- Explored how words connect to form meaningful sentences.

### Module 6 – Sentiment Analysis
**Responsible Member: Cris**

- Analyzed the sentiment of news articles.
- Explored positive, negative, and neutral language.
- Examined how sentiment analysis can help interpret news coverage.

### Module 7 – News Classification
**Responsible Member: Mohmmad**

- Applied machine learning models to classify news articles.
- Trained and evaluated text classification models.
- Compared model performance using evaluation metrics.
- Analyzed classification results and errors.

### Module 8 – Named Entity Recognition
**Responsible Member: Mohmmad**

- Applied Named Entity Recognition (NER).
- Identified people, organizations, locations, and other entities.
- Explored how entity extraction provides additional information about news articles.

## 4. Technologies and Libraries

The project uses:

- Python
- Google Colab
- Pandas and NumPy
- NLTK
- spaCy
- Scikit-learn
- Matplotlib

These tools support data processing, NLP analysis, visualization, machine learning, and model evaluation.

## 5. How to Run the Project in Google Colab

### Step 1: Download the Notebook

Download the completed `ITAI2373_NewsBot_Midterm.ipynb` file from this GitHub repository.

### Step 2: Open Google Colab

Visit [Google Colab](https://colab.research.google.com/).

Select **File → Upload notebook**, then choose the downloaded `.ipynb` file.

### Step 3: Download the Dataset

Visit the [BBC News Classification dataset on Kaggle](https://www.kaggle.com/competitions/learn-ai-bbc/data).

Download the dataset and extract the files if necessary.

Locate:

`BBC News Train.csv`

### Step 4: Run the Notebook

In Google Colab:

1. Select **Runtime → Run all**.
2. When the dataset upload prompt appears, upload `BBC News Train.csv`.
3. Allow the notebook to install or load the required NLP libraries and resources.
4. Wait for the eight modules to finish executing.
5. Review the generated outputs, visualizations, and model evaluation results.

**Note:** The notebook uses a CSV upload prompt, so access to the project team's personal Google Drive is not required.

## 6. Project Results and Outputs

The NewsBot Intelligence System demonstrates the following:

- News dataset exploration and category distribution.
- Cleaned and preprocessed article text.
- TF-IDF feature extraction and important-word analysis.
- Part-of-Speech tagging results.
- Dependency parsing and sentence analysis.
- Sentiment analysis of news articles.
- News classification predictions and model evaluation.
- Named Entity Recognition results.
- Integration of multiple NLP techniques into a NewsBot workflow.

The notebook displays the actual results after execution.

## 7. Challenges and Learning Outcomes

During this project, our group learned how different NLP techniques can be combined into one system.

Some important challenges included understanding text preprocessing, interpreting grammatical relationships, comparing classification models, and integrating different module outputs.

We also learned that NLP systems have limitations. News articles may contain ambiguous language, overlapping topics, and mixed sentiment, which can affect the accuracy of automated analysis.

The project improved our understanding of Python programming, NLP workflows, machine learning evaluation, and collaborative project development.

## 8. Real-World Applications

The NewsBot Intelligence System can support several real-world applications:

- **News organizations:** Automatically categorize articles by topic.
- **Businesses:** Analyze news coverage and identify company mentions.
- **Researchers:** Study news trends and extract useful information.
- **Media monitoring:** Analyze sentiment and identify important people, organizations, and locations.

## 9. Ethical Considerations

Automated NLP systems may produce incorrect classifications or misinterpret the sentiment of news articles.

Training data can also contain biases that affect model predictions. Therefore, NewsBot results should be interpreted carefully, and human review is important when using automated analysis for real-world decisions.

## 10. Conclusion

The NewsBot Intelligence System successfully brings together eight NLP modules to demonstrate how news articles can be processed, analyzed, and classified.

Each group member contributed to two modules, and the project provided practical experience with text preprocessing, feature extraction, linguistic analysis, machine learning, and named entity recognition.

Overall, this project helped us understand how different NLP techniques work together to build a complete news intelligence workflow.
