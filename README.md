# question-classifier
Lightweight Python tool to detect whether a question is factual, opinion-based, or math-related — with built-in math solving and easy integration for AI/LLM enhancements.

# Question Classifier

A simple Python script that takes a user question, classifies it as **factual**, **opinion**, or **math**, and returns an appropriate response.

## Features
- Classifies input text into 3 categories.
- Solves basic math expressions.
- Can be extended with API/LLM support.

- ## Adding API/LLM Support:

Integrate OpenAI GPT API or Hugging Face Transformers to replace the simple keyword logic with a fine-tuned text classification model.

Use an API call to classify the question type with higher accuracy.

For factual/math queries, forward to specialized APIs:

Math → WolframAlpha API or Python evaluation sandbox.

Factual → Knowledge graph or LLM prompt for verified info.

Opinion → LLM prompt for nuanced discussion.


