### Myers-Briggs Type Indicator (MBTI) Personality Prediction

#### Abstract
This project introduces a machine learning approach to predict Myers-Briggs Type Indicator (MBTI) personality types based on survey responses. Leveraging advanced algorithms, our model accurately classifies individuals into their respective personality types, contributing to the intersection of psychology and artificial intelligence.

#### Introduction
The MBTI personality prediction project utilizes machine learning methodologies to predict personality types based on individuals' behavioral patterns and preferences. The MBTI divides individuals into 16 personality types using four pairs of characteristics. By analyzing a dataset of MBTI survey responses, the machine learning model is trained to accurately classify individuals into one of the 16 personality types. This project aims to deepen our understanding of human behavior and has potential applications in psychology, team dynamics, and personalization. It showcases the intersection of psychology and artificial intelligence, highlighting the predictive capabilities of machine learning in categorizing human personality traits.

#### Dataset Description
The dataset focuses on exploring the Myers Briggs Type Indicator (MBTI), categorizing individuals into one of 16 distinct types based on preferences in four axes: Introversion/Extroversion, Intuition/Sensing, Thinking/Feeling, and Judging/Perceiving. The dataset consists of over 8600 rows, with each row representing a person's MBTI type along with a section containing the last 50 posts made by that person.

#### Project Description
##### Data Preprocessing
- **Regular Expressions (Regex):** Powerful tool used for defining search patterns within text data.
- **Stop Words Removal:** Filtering out common words considered non-informative or irrelevant.
- **Tokenization:** Process of breaking down text into smaller units (tokens).
- **Padding:** Adding extra elements to input data sequences to make them uniform in length.

##### Handling Imbalanced Data
- **Random Oversampling:** Augmenting instances in the minority class until it matches the count of the majority class.

##### Our Approach
- **CNN for Text Classification:** Utilizing Convolutional Neural Networks to classify text.
- **BERT (Bidirectional Encoder Representations from Transformers):** Incorporating BERT for language representation and classification tasks.

##### Difference between Our Approach and Reference Papers
- Our approach mandates an exact match across all four traits for a prediction to be deemed correct.
- We utilized CNN and BERT, while reference papers employed RNN and SBERT respectively.

##### Model Evaluation
- Our accuracy ranged from 55% to 69%, with stringent criteria for true positives and consideration of imbalanced data.
- Reference papers achieved accuracies ranging from approximately 65% to 70%.

#### Analysis
- Strengths: Achieved 70% accuracy in predicting MBTI personality types.
- Areas for Improvement: More effective handling of imbalanced datasets and exploring larger language models.
- Future Work: Balancing datasets with authentic data, streamlining workflow, and developing user-friendly applications.

#### Conclusion
Despite challenges, our project demonstrates the potential of machine learning in predicting MBTI personality types. Future efforts aim to improve dataset balance and explore advanced language models for enhanced accuracy.

### Acknowledgments
- Adapted from papers: "Personality Type Based on Myers-Briggs Type Indicator with Text Posting Style by using Traditional and Deep Learning" and "Personality Prediction Based on Contextual Feature Embedding SBERT".
