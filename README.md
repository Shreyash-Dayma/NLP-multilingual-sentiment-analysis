## Task : Multilingual Sentiment Analysis

**Objective:**  
Use a pretrained BERT model — already fine-tuned for multilingual sentiment analysis — to classify a sentence in Spanish, Italian, or any other supported language.

**Model Used:**  
Hugging Face model: nlptown/bert-base-multilingual-uncased-sentiment



**How to Run:**
1. Install dependencies:
   ```bash
   pip install torch transformers

2. Run the script:

    python multi-lingual.py


3. Example Output:

    Sentence: Me encanta este producto, es fantástico
    Predicted Sentiment: 5 star(s)
