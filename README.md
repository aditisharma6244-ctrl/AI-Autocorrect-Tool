# ✨ AI Autocorrect Tool

An NLP-based autocorrect application designed to detect and correct
spelling errors in user-provided text.

## 🎯 Objective

The objective of this project is to develop an AI-driven text
correction system that identifies common spelling errors and produces
a corrected version of the input text.

## 🚀 Features

- Automatic spelling correction
- Detection of changed words
- Correction statistics
- Interactive text input
- Correction rate calculation
- Model evaluation
- Visualization of evaluation results

## 🧠 How It Works

The system follows this workflow:

User Input
↓
Text Processing
↓
Spelling Detection
↓
Autocorrection
↓
Correction Analysis
↓
Evaluation

## 🛠️ Technologies Used

- Python
- Natural Language Processing
- TextBlob
- Regular Expressions
- IPyWidgets
- Matplotlib
- Google Colab

## 📊 Evaluation

The autocorrect system is evaluated using a small test dataset
containing intentionally misspelled sentences.

The evaluation compares the predicted corrected sentence with the
expected correction and calculates exact-match accuracy.

## 💡 Example

### Input

```text
I am lerning machne lerning.
### Output

```text
I am learning machine learning.
### Corrections Detected
lerning → learning
machne → machine

