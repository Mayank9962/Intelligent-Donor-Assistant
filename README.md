# 🧠 AI Text & Image Generator using AWS Bedrock

This project provides Python scripts to generate text and images using Amazon Bedrock’s Titan models. It utilizes the boto3 SDK to communicate with AWS services and perform AI-based content generation.

## 🔥 Features

- Generate text using Amazon Titan Text Lite
- Create images using Amazon Titan Image Generator
- Lightweight Python implementation using boto3
- Output stored locally in organized folders

---

## 🧰 Requirements

- AWS account with Bedrock access enabled
- Python 3.8 or higher
- boto3 Python package

## 🚀 Installation

### Clone the repository

git clone https://github.com/mayankbairagi123/donor-ai-bedrock.git
cd donor-ai-bedrock

Install dependencies

pip install -r requirements.txt

⚙ Usage

Text Generation (Titan Text Lite)
python textgen_bedrock.py
Image Generation (Titan Image Generator)
python smart_imagegen.py
Generated outputs will be saved in the output/ directory.

📦 Sample Output (Text)

{
  "generatedText": "Generative AI is reshaping industries by enabling faster and smarter content creation."
}

<img width="1024" height="1024" alt="generated_image" src="https://github.com/user-attachments/assets/998ea6e3-9f03-48f6-95ec-03c5411fbff1" />

📌 Notes

Ensure your AWS credentials are properly configured using environment variables or AWS CLI before running the scripts.
