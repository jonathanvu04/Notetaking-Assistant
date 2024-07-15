# Notetaking-Assistant
LA Hacks 2023 Project

This is our LAHacks 2023 submission created by Anish Goel, Jonathan Vu, Christina Pham, and Sophia Liang.

We introduce to you a revolutionary web-based platform that uses cutting-edge speech recognition technology to automatically transcribe audio files into detailed notes.

With our platform, you can easily upload any audio file format, such as mp3, and watch as our AI-powered speech recognition engine transcribes every word into clear and accurate text. Our platform is perfect for anyone who wants to improve their learning or productivity, by converting audio files into more efficient notes. It's especially useful for students who need to review lectures, professionals who attend meetings and conferences, and anyone who wants to improve their note-taking skills. Our interactive speech-to-analysis website is designed to be user-friendly and accessible to everyone, whether you're a tech-savvy individual or not.

To check out our app, users need to install the required modules and set up a virtual environment to get it to work properly.

## Features

- User interface built with Streamlit
- Integration with Cohere for natural language processing
- Audio processing with Whisper and pydub

## Requirements

Make sure you have the following installed:

- Python 3.6 or higher
- pip (Python package installer)

## Installation

Follow these steps to set up your environment and install the required modules.

### 1. Clone the Repository

Clone this repository to your local machine:

git clone https://github.com/yourusername/Notetaking-Assistant.git
cd Notetaking-Assistant

### 2. Set Up a Virtual Environment
It's recommended to use a virtual environment to manage dependencies. You can create and activate a virtual environment using the following commands:

For macOS and Linux:
python3 -m venv env
source env/bin/activate

For Windows:
python -m venv env
.\env\Scripts\activate

3. Install Required Modules
Once the virtual environment is activated, install the necessary modules:
pip install streamlit
pip install cohere
pip install openai-whisper
pip install pydub

4. Run the Application
To run the application, use the following command:
streamlit run demo.py
