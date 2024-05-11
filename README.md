# Meta Llama-3-Powered Voice Chatbot
A voice chatbot built with Meta Llama 3 and Ollama Python Library

This repository includes a Python program that interacts with the Meta Llama 3 model via Ollama Python Library to obtain a response for any request from a user and then convert the text response to an audio response. This version has been tested on Windows 10.

Please watch this YouTube video tutorial to learn more about this code:    
  
At first, you will need to download and install Ollama from the official website at https://ollama.com. Then, download the Meta Llama 3 model with this command,  

```console
ollama pull llama3
```

Once that is done, we can start Ollama and use the Llamma 3 model in Python code, 

```console
ollama serve
```

If you would like to use another large language model, you can pull it in the same way and change the code accordingly. 

Before you can run this code on your computer, you will need to install the following Python packages:

```console
pip install ollama
pip install speechrecognition gtts pyaudio pygame
```

If you have Python 3.12 or newer, also install the "setuptools" package,       

```console
pip install setuptools   
