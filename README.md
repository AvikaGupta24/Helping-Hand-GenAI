# Helping-Hand-GenAI
Helping Hand is an AI-powered study assistant that promotes independent learning through guided homework support, concept explanations, and personalized practice questions rather than giving straightup answers to the student, it nurtures independent thinking.

As artificial intelligence becomes increasingly accessible to students, it can be tempting to rely on AI-generated answers without fully understanding the underlying concepts.
Helping Hand explores an alternative approach: using AI to guide the learning process rather than replace independent thinking.

 - The application provides grade-appropriate educational assistance through an interactive interface developed using Python, Streamlit and the OpenAI API.

## Core Principles

- Learning over answers: Encourage students to work through problems rather than simply receiving final solutions.
- Conceptual understanding: Prioritize explanations, reasoning and real-world examples.
- Personalized assistance: Adapt support based on the student's subject, topic and grade level.
- Active learning: Reinforce knowledge through practice questions and immediate feedback.

## Key Features
1. Homework Help
Provides AI-generated, step-by-step guidance to help students approach homework questions without directly revealing the final answer.

2. Understand a Concept
Explains academic concepts using accessible language, examples and analogies appropriate to the student's grade level.

3. Practice Questions
Generates multiple-choice practice questions based on the student's selected subject, topic, grade level and difficulty.
Students can select the number of questions, submit their responses and receive a score.

4. Personalized Learning
Allows users to customize their experience by selecting their academic subject, topic and grade level.

5. PDF Text Extraction
Supports uploading text-based PDF documents, extracting their contents and saving the extracted text for use as supporting study material.
PDF processing is designed for digitally readable text rather than scanned-image OCR. Some document-context functionality requires further refinement.

## Technologies Used
Python: Application logic
Streamlit: Interactive user interface
OpenAI API: AI-generated educational guidance and practice questions
PyPDF2: Text extraction from PDF documents
python-dotenv: Environment variable management

## How to Run
create an environment
install necessary libraries -> pip install -r requirements.txt
Create a .env file in the project directory and add your OpenAI API key in the following format:
  OPENAI_API_KEY=your_api_key_here

Start the application:

## Limitations
Helping Hand is an educational prototype. AI-generated explanations and questions may occasionally contain inaccuracies and should be reviewed critically.
The application requires an internet connection and access to the OpenAI API. API usage may incur charges.
Some features, including uploaded-document context handling and quiz-response parsing, require further testing and refinement.

## Project Purpose
Helping Hand was developed to explore how artificial intelligence can make educational assistance more accessible while encouraging students to remain actively engaged in the learning process.
