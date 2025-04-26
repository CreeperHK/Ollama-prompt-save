# Ollama-prompt-save
Save for my used prompt for personal use in Ollama. Feel free to use for your model.

## How to use the prompt
1. Install Ollama first -> https://ollama.com/download
2. Download the base model that I use in the prompt.
	For example, if my prompt uses 'gemma3:12b-it-qat', you must download 'gemma3:12b-it-qat' first with this command:
	```bash
	ollama run gemma3:12b-it-qat
	```
3. Create a new model base on the prompt and the base model, using this command:
	```bash
	ollama create <Model Name> -f <./path>
	```
4. You can now test run on the model by this command
	```bash
	ollama run <Model Name>
	```
