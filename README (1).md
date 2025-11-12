Comment Categorization & Reply Assistant Tool
Objective

To design a mini Natural Language Processing (NLP) project that reads user comments (e.g., from social media or product reviews), analyzes their emotion or intent, and automatically classifies them into categories such as Praise, Criticism, Spam, or Hate.

The tool also suggests empathetic auto-replies to help brands, educators, or creators respond efficiently and professionally to different types of comments.

Project Overview
Step	Description
1. Dataset Creation	Built a labeled dataset of 160+ comments across 8 emotional/intent categories.
2. Preprocessing	Cleaned text (lowercase, punctuation removal, stopword removal).
3. Feature Extraction	Used TF-IDF Vectorization to convert text into numerical features.
4. Model Training	Trained a Logistic Regression classifier to detect comment categories.
5. Evaluation	Measured accuracy using classification report and confusion matrix.
6. Auto-Reply System	Added predefined polite replies for each category.
7. Visualization	Displayed confusion matrix heatmap for category accuracy.
Comment Categories

Praise

Support

Constructive Criticism

Hate / Abuse

Threat

Emotional

Irrelevant / Spam

Question / Suggestion

Auto-Reply Templates
Category	Suggested Reply
Praise	"Thank you! We're glad you enjoyed it."
Support	"Your support means a lot — thank you."
Constructive Criticism	"Thanks for your feedback — we'll work on improving."
Hate/Abuse	"We care about respectful conversations — please be respectful."
Threat	"We take such concerns seriously and will review them promptly."
Emotional	"Thank you for sharing — your feelings matter to us."
Irrelevant/Spam	"This appears promotional and has been flagged as spam."
Question/Suggestion	"Great question! We'll consider this for our next post."
Tech Stack

Language: Python

Libraries: pandas, scikit-learn, nltk, matplotlib, seaborn

Algorithm: Logistic Regression (multi-class classification)

Environment: Google Colab / Jupyter Notebook

Model Evaluation

Accuracy: High performance across all categories

Visualization: Confusion Matrix Heatmap

Dataset Size: 160 comments (balanced across categories)

Files in This Repository
File Name	Description
Comment_Categorization_Submission.ipynb	Main notebook (training, evaluation, and auto-reply)
comments_embedded.csv	Embedded dataset (auto-created on run)
comment_model.pkl	Trained model (for reusing predictions)
vectorizer.pkl	TF-IDF vectorizer (for feature transformation)
sample_predictions.csv	Example categorized output
How to Run

Clone or download this repository.

Open the notebook in Google Colab or Jupyter Notebook.

Run all cells sequentially (no uploads required — dataset is auto-created).

The model will train, evaluate, and show sample predictions with auto-replies.

Example Output
Comment: Awesome content! Keep it up!
Category: Praise
Suggested Reply: Thank you! We're glad you enjoyed it.

Comment: This is nonsense, worst ever.
Category: Hate/Abuse
Suggested Reply: We care about respectful conversations — please be respectful.

Visuals

Confusion Matrix Heatmap

Text Preprocessing Overview

Auto-reply Output Examples

(You can add screenshots from your Colab output here.)

Future Improvements

Add Streamlit or Gradio UI for real-time comment input

Integrate with social media APIs (YouTube, Instagram, etc.)

Experiment with BERT/Transformer models for higher accuracy

Generate AI-based smart replies using ChatGPT or OpenAI API

Author

Piyush Gupta
Indore, India
Email: gupta.piyush2559@gmail.com

LinkedIn: https://www.linkedin.com/in/piyush-gupta-09ba79265

GitHub: https://github.com/guptapiyush7067

Summary

This project demonstrates a complete NLP workflow for comment classification and automated response generation.
It is beginner-friendly, well-documented, and designed for academic and professional evaluation in AI, ML, or EdTech settings.
