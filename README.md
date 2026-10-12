PART A: Environment Setup and Model Selection

The required Python libraries, including PyTorch, Hugging Face Transformers, and Gradio, are installed in Google Colab. A pretrained Transformer-based conversational model, Qwen2.5-1.5B-Instruct, is selected from Hugging Face. The tokenizer and model are loaded to process user inputs and generate responses. The model is initialized successfully and prepared for chatbot development.

PART B: Prompt Handling and Response Generation

A response-generation function is created to accept user messages and generate suitable answers. The input prompt is formatted according to the model's chat template and converted into tokens using the tokenizer. The model processes the input and generates a response, which is decoded into readable text. Conversation history is included to help the chatbot understand follow-up questions. Five different prompts are tested to evaluate the relevance and clarity of the generated responses.

PART C: Building the Chatbot Interface

Gradio is used to develop an interactive web-based chatbot interface. The response-generation function is connected to the Gradio ChatInterface, allowing users to enter messages and view the model's responses. The interface includes a title, description, message input box, and conversation display area. Conversation history is maintained to support continuous interaction. The application is launched, and users can access the chatbot through a web browser.

PART D: Testing and Deployment

The chatbot is tested using factual, conversational, and task-oriented prompts to evaluate its response quality. Follow-up questions are asked to check whether the chatbot can maintain context across messages. The responses are examined for relevance, clarity, and accuracy. The application is launched using Gradio's sharing feature to obtain a temporary public link for demonstration. The source code, README file, requirements file, screenshots, and sample outputs are saved for submission. The limitations of the chatbot, such as inaccurate answers, processing requirements, and dependence on internet access, are also identified.

# 24ADI006_24BAD409_EXP_10
