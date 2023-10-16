# chatgpt task

Simple script to use ChatGPT on your own files. I have followed this tutorial to implement a simple solution
[YouTube Video](https://youtu.be/9AXP7tCI9PI).

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip3 install langchain openai chromadb tiktoken unstructured
```
Modify `constants.py.` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys).

I have added the data files into the folder data. But due to billing I have had to only use a small amount of the csv file to test. 

## Example usage
Test reading `data/data.txt` file.
```
> python chatgpt.py "what is mthe highest income?"
82800
```
