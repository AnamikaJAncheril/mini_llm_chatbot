# mini_llm_chatbot


# 🧠 Mini LLM Chatbot – Gemma 2B (Local Inference)

This project is a simple **local LLM chatbot** built using **Google’s Gemma-2B** model.
It runs fully in your Colab or local system using the **Hugging Face Transformers** library.

The chatbot takes user input, sends it to the model, and prints the generated response.

## 🚀 Features

* Loads **Gemma-2B** locally using Hugging Face.
* Simple text-based chat loop in Python.
* No UI — pure terminal chatbot.
* Supports temperature, max tokens, and sampling.

## 🧩 How It Works

1. Load tokenizer and model (`google/gemma-2b`).
2. Convert user input to tokens.
3. Generate output using the model.
4. Decode and print the response.
5. Loop until user types `exit` or `quit`.

## 📂 Project Purpose
A minimal example to understand:
* How to load an LLM locally
* How to generate text
* How to build a simple chatbot loop

Perfect for beginners learning LLM fundamentals.

