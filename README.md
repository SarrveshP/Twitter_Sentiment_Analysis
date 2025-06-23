# Twitter Sentiment Analysis

## Dataset

- **Source**: [Kaggle - Twitter Entity Sentiment Analysis]
- The dataset comprises tweets tagged with sentiment labels relevant to specific entities.
- **Key features**:
  - Tweet text
  - Topic/entity
  - Sentiment label (Positive, Negative, Neutral, Irrelevant)
- **Preprocessing considerations**:
  - Handling emojis, URLs, user mentions, and hashtags
  - Dealing with informal language and slang

---

## Tools & Libraries Used

- **Programming Language**: Python  
- **Data Manipulation**: `pandas`, `numpy`  
- **Visualization**: `matplotlib`, `seaborn`  
- **Text Processing**: `nltk`, `re`, `string`  
- **Machine Learning**: `scikit-learn`  
- **Others**: `WordCloud`, `collections`

---

## Project Workflow

1. **Data Loading**  
   - Imported the dataset and explored its structure using `pandas`.

2. **Text Preprocessing**  
   - Lowercased all text  
   - Removed punctuation, URLs, mentions, hashtags, and stopwords  
   - Applied tokenization and stemming

3. **Exploratory Data Analysis (EDA)**  
   - Generated visualizations such as:
     - Word clouds for overall and sentiment-specific tweets  
     - Sentiment distribution across topics  
     - Heatmaps and box plots for text statistics  

4. **Text Vectorization**  
   - Transformed tweet text into numerical format using **TF-IDF Vectorizer**

5. **Model Training**  
   - Applied **Logistic Regression** for multiclass classification

6. **Model Evaluation**  
   - Assessed performance using:
     - Accuracy Score  
     - Confusion Matrix  
     - Classification Report

---

## Key Learnings

- Practical experience in preprocessing noisy and unstructured social media text  
- Application of TF-IDF for converting textual data into meaningful numerical vectors  
- Understanding the impact of class imbalance in sentiment datasets  
- Effective use of **Logistic Regression** for text classification tasks

---

## Output Metrics

- **Model Accuracy**: Achieved high accuracy on the test set  
  - Word Clouds for each sentiment category  
  - Sentiment Distribution Charts  
  - Confusion Matrix to evaluate model performance

---

