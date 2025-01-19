
# Function Calling with LangChain and Google Generative AI

This project demonstrates the use of LangChain and Google Generative AI in a Python environment. The notebook provides an example of setting up and working with these tools for natural language processing and AI-powered applications.

## Features
- **Dependency Management**: Installing required libraries such as `langchain`, `langchain_community`, and `langchain_google_genai`.
- **Environment Setup**: Configuring environment variables, including `GOOGLE_API_KEY`.
- **Integration with Google Generative AI**: Initializing and utilizing the `ChatGoogleGenerativeAI` model (`gemini-1.5-flash`).

## Installation
To run this notebook, follow these steps:
1. Clone this repository or download the notebook file.
2. Open the notebook in Google Colab or your preferred Jupyter environment.
3. Install the required libraries by running:
   ```bash
   !pip install langchain langchain_community langchain_google_genai
   ```
4. Set up the required environment variables, such as:
   ```python
   import os
   os.environ['GOOGLE_API_KEY'] = '<Your Google API Key>'
   ```

## Usage
1. Import the required modules:
   ```python
   from langchain_google_genai import ChatGoogleGenerativeAI
   ```
2. Initialize the language model:
   ```python
   llm = ChatGoogleGenerativeAI(model='gemini-1.5-flash', verbose=True)
   ```

## Requirements
- Python 3.10 or higher
- Libraries:
  - `langchain`
  - `langchain_community`
  - `langchain_google_genai`
- A valid Google API key

## Author
This notebook was created by Hareem Zahra.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
