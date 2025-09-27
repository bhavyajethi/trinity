# **CSV Header Description Generator**

## **Model Used and Reasoning**
For this assignment, I used **Ollama** as the offline language model to generate descriptive texts for CSV headers. Other open-source models like GPT-2, DistilGPT, and Flan often produced inaccurate or irrelevant descriptions for this specific task. Larger models such as Mistral provided better results but were too resource-intensive and frequently crashed my system. **Ollama** runs efficiently on my local machine, produces coherent and accurate descriptions, and works completely offline without any cloud API, making it reliable for this use case.

## **How to Run the Script**
1. data.csv should be in the same directory as the script.  
2. Run the Python script:  
   ```bash
   python main.py
3. header_descriptions.txt is generated as the output file.
