# Chatbot for Your Data
## Introduction
In this project, you will create a chatbot for your own pdf file using Flask, a popular web framework, and LangChain, another popular framework for working with large language models (LLMs). The chatbot you develop will not just interact with users through text but also comprehend and answer questions related to the content of a specific document.

TRY THE DEMO APP
https://chatbot-for-own-data.xs6r134s1i6.us-east.codeengine.appdomain.cloud/

# Setting up and understanding the user interface
In this project, the goal is to create a chatbot with an interface that allows communication.

First, let's set up the environment by executing the following code:

1. pip3 install virtualenv 
2. virtualenv my_env # create a virtual environment my_env
3. source my_env/bin/activate # activate my_env

The frontend will use HTML, CSS, and JavaScript. The user interface will be similar to many chatbots you see and use online. The code for the interface is provided and the focus of this guided project is to connect this interface with the backend that handles the uploading of your custom documents and integrates it with an LLM model to get customized responses. The provided code will help you to understand how the frontend and backend interact, and as you go through it, you will learn about the important parts and how it works, giving you a clear understanding of how the frontend works and how to create this simple web page.

Run the following commands to retrieve the project, give it an appropriate name, and finally move to that directory by running the following:

1. git clone https://github.com/sinanazeri/build_own_chatbot_without_open_ai.git
2. mv build_own_chatbot_without_open_ai build_chatbot_for_your_data
3. cd build_chatbot_for_your_data

installing the requirements for the project

1. pip install -r requirements.txt

Have a cup of coffee, it will take 5-10 minutes to install the requirements (You can continue this project while the requirements are installed).

# Create worker.py and server.py documents
