# ChatGPT API in Python

This project is an example of how to use the OpenAI API to create a chatbot using the GPT-3.5 Turbo model. The application is written in Python and utilizes the OpenAI, Typer, and Rich libraries.
The creator of this code is MoureDev.
The following is the link of the tutorial and the author's contacts:
https://moure.dev/

Crea una APP con PYTHON y CHATGPT desde cero:
https://www.youtube.com/watch?v=b8COygWdvmw

## Installation

To install the necessary libraries, run the following command:

```bash
pip install openai typer[all] rich
```

### Creating a Python Virtual Environment

#### Windows

1. Open the command prompt by typing "cmd" in the search bar and pressing Enter.
2. Navigate to the directory where you want to create your virtual environment using the `cd` command.
3. Type the following command to create a virtual environment with the name "myenv":
```bash
python -m venv myenv
```
4. Activate the virtual environment by running the activate script:
```bash
myenv\Scripts\activate
```
You can now install packages and run Python scripts within the virtual environment. To exit the virtual environment, simply type:
```bash
deactivate
```

#### Mac

1. Open the Terminal application.
2. Navigate to the directory where you want to create your virtual environment using the `cd` command.
3. Type the following command to create a virtual environment with the name "myenv":
```bash
python3 -m venv myenv
```
4. Activate the virtual environment by running the activate script:
```bash
source myenv/bin/activate
```
You can now install packages and run Python scripts within the virtual environment. To exit the virtual environment, simply type:
```bash
deactivate
```

The application will prompt you for input and respond with generated text based on the GPT-3.5 model. Use the `exit` command to quit the application or `new` to start a new conversation.


## Useful links

- OpenAI module: https://github.com/openai/openai-python
- ChatGPT API documentation: https://platform.openai.com/docs/api-reference/chat
- Typer: https://typer.tiangolo.com
- Rich: https://rich.readthedocs.io/en/stable/
