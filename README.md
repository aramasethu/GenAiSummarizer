# GenAiSummarizer
LLM chatbot that will give a brief summary of website / doc 


# Setup
Create a virtual environment and install the libraries specified
```
pip install -r requirements.txt
```
If the following error is encountered
```
ERROR: Failed building wheel for chroma-hnswlib
```
then try
```
export HNSWLIB_NO_NATIVE=1 
```
as per guidance [here](https://stackoverflow.com/a/75870031).
