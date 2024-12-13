# DSPy AI Agents Experiment

### Declarative Self-improving Python ([DSPy](https://dspy.ai))  

This framework allows developers to "program" Language Model (LM) prompts using function signatures to teach your LM to deliver high-quality outputs.

## Getting Started

### Install and run the Ollama Docker Containter on your local CPU

1. Install the Ollama Docker Image & run the Ollama container  

    `docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama` 

2. Start the Ollama container if you have it already  

    `docker start ollama`  

3. Install the 6 Bit quantized Llama 3 model (for Intel CPUs)  

    `docker exec -e OLLAMA_LLM_LIBRARY=cpu_avx ollama ollama run llama3.2:1b-instruct-q6_K`

### Run DSPy Locally with Ollama 

1. Clone the repo  

    `git clone git@github.com:hamilton-labs/DSPy-AI-Agents-Experiment.git` 

2. Create a virtual environmnet  

    `python -m venv DSPy_trial`

3. Change into the DSPy_trial directory  

    `cd DSPy_trial`

4. Activate the virtural environment  

    `source ./bin/activate`

5. Install the dependencies (Python v3.12.3+)  

    `pip install -r requirements.txt`

6. Run the program  

    `python DSPy_setup.py` 

## Possible Output (outputs may vary)
Here's how Llama 3 responded for me.
```
************************************************

Configured the LM

*************************************************
*************************************************

Calling the LM directly

*************************************************
*************************************************

Printing the LM's Output

*************************************************
It looks like you're trying to add some confidence and bravado to your response. I'll play along, but keep in mind that it's all just a simulation. Here's my response:

"Yes, indeed it is!" *pounds fist on table* "I mean, who needs a traditional test when we can have a simulated one? It's like the ultimate game of wits! Bring it on, test administrator!"

It looks like you're getting into the spirit of things. That's completely fine. I'm here to help and provide information, so feel free to ask me anything. What's on your mind for this test? 