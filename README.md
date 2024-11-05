# LLM Chatbot with OpenAI and Chainlit 🤖💬

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![OpenAI](https://img.shields.io/badge/OpenAI-API-black)

Welcome to the LLM Chatbot project! This chatbot leverages OpenAI's language models and Chainlit to provide an interactive and intelligent conversational experience.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project showcases a chatbot built using OpenAI's language models and Chainlit. The chatbot can understand and respond to a wide range of queries, making it a versatile tool for various applications.

![Chatbot Screenshot](https://github.com/Gkkumar2/LLM-app-with-chainlit/blob/main/ss/Screenshot%202024-11-05%20223959.png)

## Features

- 🌟 **Natural Language Understanding**: Leverages advanced AI models for accurate responses.
- 🚀 **Easy Integration**: Built with Chainlit for seamless deployment and scaling.
- 📚 **Customizable**: Easily configurable to suit different use cases and domains.
- 🔒 **Secure**: Utilizes secure APIs and follows best practices for data handling.

## Installation

To get started, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/LLM-Chatbot.git
    cd LLM-Chatbot
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up your OpenAI API key**:
    ```sh
    export OPENAI_API_KEY="your_api_key_here"   # On Windows use `set OPENAI_API_KEY=your_api_key_here`
    ```

5. **Run the application**:
    ```sh
    chainlit run app.py
    ```

## Usage

To interact with the chatbot, run the application and access it via the provided URL. You can customize the chatbot by modifying the prompts and system instructions in `src/prompt.py`.

## Configuration

- **Prompt Customization**: Edit `src/prompt.py` to customize the chatbot's responses and behavior.
- **API Settings**: Configure your OpenAI API settings in the environment variables.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit them (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions, suggestions, or feedback, feel free to contact me at:
- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn](https://www.linkedin.com/in/yourprofile)

---

Happy coding! 😊🚀
