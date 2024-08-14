# LLaMA Assistant for Mac

A simple assistant for Mac that uses llama-cpp-python to assist you. This uses pretty much 90% of the code from [here](https://github.com/patrickloeber/ai-typing-assistant/blob/main/main.py) but replaces the ollama stuff with llama-cpp-python.

## Why?

Because I wanted a more pythonic solution.

## Setup

Create a virtual environment and follow the steps below.

1. Install llama-cpp-python

`CMAKE_ARGS="-DGGML_METAL=on" pip install llama-cpp-python`

2. Install pynput and pyperclip

`pip install pynput pyperclip`

3. Run main.py

Note: These steps are for macos. If you are on windows or linux, you will need to install llama-cpp-python differently.

