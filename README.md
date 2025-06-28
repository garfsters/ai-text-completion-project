# AI Text Completion App

This is a simple Python-based text completion application that uses Cohere’s Generative AI API. It lets you enter any prompt through the terminal, sends it to Cohere’s language model, and prints out the generated response. The app is designed to help experiment with how Generative AI processes different types of inputs, from stories to explanations to summaries.

## Features

- Accepts user prompts right in the terminal
- Generates AI completions using Cohere’s language model
- Runs in a loop so you can try multiple prompts in one session
- Handles empty inputs and exits cleanly when you type `exit`
- Lets you adjust generation parameters in the code (like temperature and max tokens) to control creativity and response length

## Example Prompts to Try
- Once upon a time, there was a robot who...
- Explain photosynthesis to a 10-year-old.
- Write a haiku about the ocean.
- Summarize this text: [insert a long passage here]
- Are Sean "Diddy" Combs and Kanye West close friends?


## Installation

1. **Clone this repo:**
    ```bash
    git clone https://github.com/your-username/ai-text-completion-project.git
    cd ai-text-completion-project
    ```

2. **Install dependencies:**
    ```bash
    pip install cohere
    ```

## Setup

1. **Get your API key:**
    - Sign up at [https://cohere.com](https://cohere.com)
    - Copy your API key from the dashboard under your account’s API Keys section.

2. **Add your API key to the script:**
    - Open `text_completion_app.py` and replace `"YOUR_API_KEY"` with your actual API key.
    - Or set an environment variable and load it in Python for more security.

## Usage

Run the app from your terminal:

```bash
python text_completion_app.py

