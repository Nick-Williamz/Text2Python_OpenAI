# English to Python Code Translation

This project is a web application that translates English tasks into Python code using OpenAI's GPT-3.5-Turbo language model and Flask, a Python web framework.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
As developers, we often come across situations where we need to translate English instructions or tasks into executable code. This web application leverages the power of AI to automate this translation process, saving time and effort.

## Prerequisites
Before getting started, make sure you have the following prerequisites:
- OpenAI API access and API key
- Python installed on your machine
- Flask installed in your Python environment

## Project Structure
The project has the following structure:
- `requirements.txt`: Required Modules
- `text2py_webui.py`: Python file containing the Flask application code
- `templates/home.html`: HTML template for rendering the output
- `README.md`: Project documentation (you're reading it!)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/washingtonBrewologist/TextToPython.git

2. Navigate to the project directory.
```bash
cd TextToPython
```
3. Install the required dependencies:
Note: Create a Conda Env if you know what your doing!

```bash
pip install -r requirements.txt
```
## Usage
Run the Flask application:

```bash
python text2py_webui.py
```

Access the application in your browser at http://localhost:5000.

Enter your API key and tasks in English.
Submit the form to generate the corresponding Python code.
