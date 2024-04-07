# Llama Blog Craft

Llama Blog Craft is a Streamlit app that generates blog content using a pre-trained language model.

## Features

- Generate blog content based on user input topic, word count, and target audience.
- Utilizes a language model to craft coherent and contextually relevant blog posts.
- Easy-to-use interface powered by Streamlit.

## Requirements

- Python 3.x
- Streamlit
- Other dependencies (specified in requirements.txt)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/llama-blog-craft.git
```

2. Install dependencies:

```bash
cd llama-blog-craft
pip install -r requirements.txt
```

3. Download the language model files and place them in a model folder within the
project directory. The model file llama-2-7b-chat.ggmlv3.q8_0.bin is required 
for generating blog content. You can obtain this model from:
[Llama-2-7B-Chat-GGML](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main).

## Usage

1. Run the streamlit app:

```bash
streamlit run app.py
```

2. Enter the blog topic, select the target audience, and specify the word count.
3. Click on the "Generate" button to generate the blog content.

## Configuration

The language model used for generating blog content is specified in model/llama-2-7b-chat.ggmlv3.q8_0.bin.
You can adjust parameters such as max_new_tokens and temperature in the get_llama_response function in app.py to fine-tune the output.

