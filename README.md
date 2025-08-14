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
   
> ### How It Works
> We load a ready-made brain (**nlptown/bert-base-multilingual-uncased-sentiment** model)  
> that already knows how to read many languages and judge if a sentence is positive or negative.  
>
> We give it a sentence — in Spanish, Italian, or other supported languages.  
>
> The tokenizer turns your sentence into numbers that the model understands  
> (because computers don’t understand words directly).  
>
> The model thinks and outputs five numbers — each number represents how likely  
> your sentence is to have **1, 2, 3, 4, or 5 stars**  
> (where **1 star = very negative**, **5 stars = very positive**).  
>
> We pick the biggest number — that’s the model’s guess for your sentence’s sentiment rating.  
>
> Finally, we print the result so you see if the text was judged **positive**, **negative**, or **neutral**.
