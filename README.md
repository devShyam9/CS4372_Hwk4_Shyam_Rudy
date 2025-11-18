# CS4372_Hwk4_Shyam_Rudy
# Text Summarization with Transformers

This project uses a pre-trained transformer model to summarize the novel **The Blue Castle** by L. M. Montgomery.  
The text is downloaded directly from Project Gutenberg and processed in Google Colab.

## Dataset
- Source: https://www.gutenberg.org/cache/epub/67979/pg67979.txt
- Format: Plain text (UTF-8)
- Loaded using a global URL as required.

## Task
I performed **text summarization** using the `facebook/bart-large-cnn` model from HuggingFace.

## Steps
1. Download the book text using `requests`.
2. Clean the text and remove the Gutenberg header.
3. Split the text into chunks (~1200 characters each).
4. Run the BART summarization pipeline on the chunks.
5. Evaluate the summaries using ROUGE-1, ROUGE-2, and ROUGE-L.

## Evaluation
ROUGE scores were computed for each summarized chunk.  
Example from the first chunk:
- ROUGE-1: ~0.41  
- ROUGE-2: ~0.38  
- ROUGE-L: ~0.33  

## How to Run
Open the provided Google Colab notebook and run each cell in order.  
The notebook handles:
- Loading the data  
- Summarization  
- ROUGE evaluation  

## Files
- `summaries.txt` -  Summaries 
- `CS4372_Shyam_and_Rudy.ipynb` - Code
-  `CS4372_Hwk4_Report_Shyam_Rudy ` - Report

