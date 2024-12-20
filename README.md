
# Spectrum Chatbot

Spectrum is a Python-based chatbot that utilizes natural language processing (NLP) to interact with users in a conversational manner. Built with various libraries, it aims to provide engaging and informative responses.

## Features

- **Natural Language Understanding:** Leverages NLTK and SpaCy for processing user inputs.
- **Random Response Generation:** Uses randomness to create dynamic responses.
- **Text Preprocessing:** Cleans and preprocesses input text to improve response accuracy.
- **Customizable:** Easy to modify and extend functionalities.

## Libraries Used

The following libraries are essential for running Spectrum:

- `nltk`: Natural Language Toolkit for working with human language data.
- `string`: Provides common string operations.
- `random`: Generates random numbers, used for selecting responses.
- `warnings`: To handle warnings generated by the code.
- `re`: Regular expressions for text searching and manipulation.
- `spacy`: Advanced NLP library for tokenization, parsing, and entity recognition.

## Installation

To get started with Spectrum, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spectrum-chatbot.git
   cd spectrum-chatbot
   
2. Install the required libraries:
   ```bash
    pip install nltk spacy

3. Download necessary NLTK Resources:
   ```bash
    import nltk
    nltk.download('punkt')
    nltk.download('wordnet')

4. Download SpaCy language model:
   ```bash
    python -m spacy download en_core_web_sm

# Usage
To run the chatbot, execute the below mentioned command in your terminal:
   ```bash
    python spectrum.py
```

# Contribution
Contributions are welcome! If you'd like to improve Spectrum, please fork the repository and submit a pull request.

# License
MIT License Copyright (c) 2024 Anjishnu0503

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

