# CS4372_Hwk4_Shyam_Rudy | Text Summarization with Transformers

This project uses a pre-trained transformer model to summarize the novel The Blue Castle by L. M. Montgomery.  
The text is downloaded directly from Project Gutenberg and processed in Google Colab.

## Dataset
-  https://www.gutenberg.org/cache/epub/67979/pg67979.txt

## Task
We performed text summarization using the `facebook/bart-large-cnn` model from HuggingFace.

## Steps
1. Download the book text using `requests`.
2. Clean the text and remove the Gutenberg header.
3. Split the text into chunks.
4. Run the BART summarization pipeline on the chunks.
5. Evaluate the summaries using ROUGE-1, ROUGE-2, and ROUGE-L.

## How to Run
Open the provided Google Colab notebook and run each cell in order.  
- Loading the data  
- Summarization  
- ROUGE evaluation  

## Files
- `summaries.txt` -  Summaries 
- `CS4372__Hwk4_Shyam_and_Rudy.ipynb` - Code
-  `CS4372_Hwk4_Report_Shyam_Rudy ` - Report

