hh.py is the mainfile to run
pest.py is the code used to create model for pest prediction
before running the project make sure you have llama-2 model in your machine,if not install it
steps to install llama2 
step1:Dowload  ollama from https://ollama.com/
step2:open cmd or ollama,  use this command pull the llama model (command: ollama pull llama2)llama-2 is the model name if you need to pull other models you use other model name
after installing ollama open your code editor (vs code preferable)
open terminal in vs code type ollama serve(this code is used to bring ollama server up)
next type streamlit run hh.py or python -m streamlit run hh.py
