# LLora-Fine-Tuning-DeepSeek1.5B-to-do-Resumes-in-Portuguese
This project fine-tunes the DeepSeek 1.5B model using LoRA (Low-Rank Adaptation) to create an AI capable of analyzing job postings and adapting Portuguese resumes, highlighting relevant skills, experiences, and keywords.

Link to code: https://colab.research.google.com/drive/14xWo-i2Aj2FoBUTzqm09YsECGz5mmMIp?usp=sharing

📌 Purpose
The main goal is to help job seekers by automatically tailoring their resumes to match a job description, increasing the chances of passing recruitment processes.

🚀 Features
Reads and analyzes job postings.

Extracts key skills, keywords, and required qualifications.

Adapts Portuguese resumes to match the job requirements.

Allows custom fine-tuning with user-provided datasets.

🛠 Technologies Used
Base Model: DeepSeek 1.5B

Fine-Tuning Technique: LoRA (via PEFT)

Language: Python

Main Libraries:

Transformers (Hugging Face)

PEFT

PyTorch

Accelerate

Datasets

SentencePiece
