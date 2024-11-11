# Python Code Generator with Gradio and Hugging Face Transformers

## Project Summary
This project implements a Python Code Generator using the `Salesforce/codegen-2B-mono` model from Hugging Face. It provides a user-friendly interface via Gradio to generate Python code based on text prompts. This tool is useful for quickly creating code snippets and helps users explore code generation capabilities in natural language processing (NLP).

## Problem Statement
With the increasing need for rapid code generation, this project seeks to provide a solution that simplifies Python code creation based on user-defined prompts. Using a pre-trained language model, users can generate code by simply entering a description. This can save time, assist with prototyping, and support learning for those new to programming.

## Business Use Cases
1. **Code Prototyping**: Quickly generate prototype code snippets based on specific requirements.
2. **Learning Assistance**: Aid new programmers by generating basic code for various tasks.
3. **Time-saving Tool**: Streamline the development process by reducing repetitive coding tasks.
4. **NLP-based Code Generation**: Explore applications of NLP models in the domain of software development.

## Skills Demonstrated
- Natural Language Processing (NLP) in Python
- Usage of Hugging Face Transformers for code generation
- Gradio for user-friendly web-based interfaces
- Fine-tuning generation parameters for high-quality output

## Domain
Software Development / NLP

---

## Approach
### 1. Code Generation Model Setup
   - **Model Selection**: Using the `Salesforce/codegen-2B-mono` model to generate Python code based on prompts.
   - **Tokenizer and Model Initialization**: Loading the model and tokenizer from Hugging Face for efficient prompt processing.

### 2. Parameter Tuning for Code Quality
   - **Tokenization**: Converting the input prompt into tokens compatible with the model.
   - **Generation Parameters**: Setting generation options such as:
      - `max_new_tokens`: Limits the length of the generated code.
      - `temperature`: Controls creativity level in the generated output.
      - `top_p`: Balances token sampling based on probability mass.
      - `repetition_penalty`: Reduces repetitive phrases for clarity in output.

### 3. Interactive Interface with Gradio
   - **Input**: Users enter a natural language prompt describing the code they want to generate.
   - **Output**: The model generates Python code based on the prompt, which is then displayed in the Gradio interface.

---
