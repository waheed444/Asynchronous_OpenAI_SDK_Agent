# 🤖 Asynchronous OpenAI SDK Agent using Gimini 

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/waheed444/OpenAI_Agent_SDK_03)


## Table of Contents 🚀

* [Official Documentation](https://openai.github.io/openai-agents-python/running_agents/)
* [Description](#description)
* [Features](#features)
* [Installation](#installation)
* [Usage](#Use-Cases-of-Asynchronous-Execution)
* [Contributing](#contributing)
* [License](#license)

## Description

This AI **Asynchronous Agent** demonstrates how to build a responsive AI assistant by integrating Google’s Gemini API through an OpenAI-compatible interface using `asynchronous execution`. It follows a modular `Agent` system design, where AI components autonomously process inputs, follow instructions, and generate intelligent responses.  

By using an OpenAI-like structure with Gemini models under the hood, this project provides a developer-friendly experience while leveraging the power and speed of `async architecture` for scalable performance.

---

## ⚡ Why Use Asynchronous Execution?

1. **Non-Blocking Operations**  
   Asynchronous code allows multiple tasks (like API calls or user inputs) to run concurrently without blocking the main execution flow.

2. **Better Performance**  
   Async execution is ideal for I/O-bound tasks (like waiting for AI responses), reducing idle time and improving overall responsiveness.

3. **Scalability**  
   Suitable for high-traffic or multi-user environments, where multiple agents or tasks need to be handled simultaneously.

4. **Smooth User Experience**  
   Async code ensures the app remains responsive, even while waiting for long operations like large model completions.

---

### Use-Cases-of-Asynchronous-Execution

- ✅ Real-time chatbots and virtual assistants  
- ✅ AI-powered web apps with multiple user interactions  
- ✅ Background task processing (e.g., queue-based systems)  
- ✅ Multi-agent AI architectures  
- ✅ High-performance microservices  
- ✅ Fast, non-blocking data processing systems

---

## Project Features

* 🤖 **Custom AI Agent:** Built using the Agent and Runner pattern for modularity and scalability.
* 🌐 **Google Gemini 2.0 Flash Integration:**  Utilizes Google's API for access to the powerful Gemini language model.
* 🔑 **Secure API Key Management:** Employs `python-dotenv` for safe and convenient API key handling.
* 🧠 **Dynamic Prompt Handling:**  Processes and responds effectively to a wide range of user prompts.
* ⚡ **Asynchronous Communication:**  Leverages `AsyncOpenAI` for optimized `asynchronous communication` with OpenAI, improving speed and responsiveness.
* 🐍 **Clean Python Codebase:**  Maintained with a focus on readability, modularity, and best practices.


## Installation

1. **Clone the Repository:**

```bash
git clone https://github.com/waheed444/OpenAI_Agent_SDK_03.git
cd OpenAI_Agent_SDK_03
```

2. **Create and Activate a Virtual Environment:**

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

3. **Install Dependencies:**

```bash
pip install -r requirements.txt
```
**OR Install Dependencies:**
```bash
pip install openai-agents python-dotenv

```
4. **Set up `.env` file:**

Create a `.env` file in the root directory and add your Gemini API key:

```
GIMINI_API_KEY  =  your_actual_gemini_api_key_here 
```

**Note:** Replace `your_actual_gemini_api_key_here` with your actual Gemini API key.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Contributing
We welcome contributions to improve this project! Please follow these steps:

1. **Fork** the repository.
2. **Create a new branch:** `git checkout -b feature-name`
3. **Make your changes** and ensure they adhere to the project's coding style and best practices.
4. **Commit your changes:** `git commit -m "Add feature"`
5. **Push to the branch:** `git push origin feature-name`
6. **Submit a pull request** with a clear description of your changes and their benefits.
If you find any issues or want to improve this project, feel free to open a [GitHub issue](https://github.com/waheed444/OpenAI_Agent_SDK_03/issues) or submit a pull request.

This repo is only for learning and exploring new things, feel free to fork it, explore, or give suggestions!

**Star ⭐ the repo if it helps you!**

---

## 🙌 Let's Connect

<p align="left">
  <a href="https://www.linkedin.com/in/waheed444/?originalSubdomain=pk)" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://github.com/waheed444" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="waheedahmad5519@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Gmail">
  </a>
</p>

---
