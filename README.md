# LLaMA Assistant for Mac

A simple assistant for Mac that uses llama-cpp-python to assist you on your predefined needs. This uses pretty much 90% of the code from [here](https://github.com/patrickloeber/ai-typing-assistant/blob/main/main.py) but replaces the ollama stuff with llama-cpp-python.

## Why?

Because I wanted a more pythonic solution and wanted to build something w/ llama-cpp-python.

## Setup

Create a virtual environment and follow the steps below.

1. Install llama-cpp-python

`CMAKE_ARGS="-DGGML_METAL=on" pip install llama-cpp-python`

Note: If you are on CUDA/ CPU, you can remove the `CMAKE_ARGS="-DGGML_METAL=on"` part and  replace with appropriate cmake args [here](https://llama-cpp-python.readthedocs.io/en/latest/#supported-backends).

2. Install pynput and pyperclip

`pip install pynput pyperclip`

3. Run main.py

Note: These steps are for macos. If you are on windows or linux, you will need to install llama-cpp-python differently.

## Acknowledgements:

- [patrickloeber/ai-typing-assistant](https://github.com/patrickloeber/ai-typing-assistant)
- [llama-cpp-python](https://github.com/abetlen/llama-cpp-python)