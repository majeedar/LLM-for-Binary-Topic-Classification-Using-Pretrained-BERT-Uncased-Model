# Tweet Relevance Filtering Model
This project explores two distinct methodologies for developing an effective tweet relevance filtering model, leveraging both traditional machine learning techniques and modern deep learning approaches. The goal is to classify tweets as relevant or non-relevant in the context of the Thameslink dataset.

# Models
## Model A: Traditional Machine Learning Approach
Overview: This model relies on traditional machine learning algorithms.
## Methodology:
Cross-validation was performed using six classifiers:
KNeighbors
Random Forest
Decision Tree
Support Vector Machine (SVM)
Logistic Regression
Gradient Boosting
Top Classifier: Logistic Regression emerged as the best-performing algorithm based on performance metrics.
Hyperparameter Tuning: Grid search was applied to fine-tune Logistic Regression by systematically exploring parameter combinations to enhance accuracy and reliability.
## Model B: Deep Learning Approach
Overview: This model utilizes a pre-trained BERT (Bidirectional Encoder Representations from Transformers) model from the Hugging Face platform.
## Methodology:
Pre-training: BERT's pre-training on large text corpora provided a strong contextual understanding of language.
Fine-tuning: The pre-trained BERT model was fine-tuned on the Thameslink dataset for three epochs.
The transformer architecture was adapted to classify tweets while preserving the rich semantic representations from pre-training.
Advantages: Model B offers a robust alternative, particularly for handling the nuanced nature of textual data, making it ideal for the classification task.
Key Highlights
Model A demonstrates the effectiveness of traditional machine learning approaches, with Logistic Regression standing out as the best-performing algorithm after fine-tuning.
Model B capitalizes on the advanced contextual understanding of BERT, providing a modern and scalable solution for tweet relevance filtering.
Dataset source: Private dataset
