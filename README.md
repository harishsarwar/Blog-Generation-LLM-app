# Generate Blogs App

## Overview
This is a Streamlit-based web app that generates blogs using the Llama 2 model. Users can input a blog topic, specify the number of words, and choose the target audience for the blog. The app leverages the `CTransformers` library for Llama 2 integration.

## Features
- Generate blogs for specific job profiles (Researchers, Data Scientists, Common People).
- Customizable input fields for blog topic, word count, and writing style.
- Powered by Llama 2 (via `CTransformers`) for high-quality blog generation.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd generate-blogs-app
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Ensure the Llama 2 model file (`llama-2-7b-chat.ggmlv3.q8_0.bin`) is placed in the `Model` directory.

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Open the app in your browser.
3. Enter the blog topic, specify the number of words, and select the blog style.
4. Click the **Generate** button to create a blog.



## Notes
- The Llama 2 model file is required and should be downloaded separately.
- Adjust the model configuration in `app.py` if needed (e.g., `max_new_tokens`, `temperature`).



