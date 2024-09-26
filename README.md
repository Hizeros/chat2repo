# Chat with GitHub repo by gaianet streamlit and pne

This is an example of building a chatbot for GitHub repo using streamlit, GaiaNet and promptulate.

## Quick Start

1. Clone the repository and install the dependencies

```shell
git clone https://github.com/Hizeros/chat2repo
```

2. Install the dependencies

```shell
pip install -r requirements.txt
```

3. Run the application

```shell
streamlit run app.py
```

# Role of each document

1. `app.py`: This is the main entry point of the application. It uses streamlit to build a chatbot interface. The chatbot is built using promptulate. The chatbot is able to chat with GitHub repo.
2. `config.py`: This is the configuration file for the application.
3. `repo_service.py`:Provides a comprehensive code warehouse management tool to handle various operations and data processing related to the code warehouse
4. `token_counter.py`:Two functions are defined to calculate the number of tokens
