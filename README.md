# Prerequisite
- Download and install [Ollama](https://ollama.com/download)
- Choose and download the suitable model through running the command in terminal.
eg. `ollama run deepseek-r1:8b` (for 8billion parameters)
    
    This command will initiate **DeepSeek** model in your terminal. For other models visit [here](https://ollama.com/library/deepseek-r1)   

- Now install **DeepSeek api** by executing the command in your terminal:

    `pip install ollama` or `npm install ollama`  


# Known issues
- **problem**: 

    Cannot find module 'vscode' or its corresponding type declarations

    **soln**:

    run `install npm vscode` 


# Run localDeepSeek
- Run open the VSCode Command Palette(`ctrl + shift + p`) and select **Start Local DeepSeek**