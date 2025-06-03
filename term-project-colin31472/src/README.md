# Indicate the name of the program
Sentiment Classifier

# Give a short description of the problem solved
This notebook implements and evaluates multiple sentiment classification models on two datasets:
- Cornell Movie Reviews (Pang/Lee polarity v2.0)
- Champaign-Urbana Yelp Restaurant Reviews (1–5 star → binary sentiment)

It compares:
- Architectures (Algorithms): DNN (baseline), LSTM, CNN, Transformer  
- Feature engineering: random embeddings, GloVe embeddings (freeze & fine‑tune), TF‑IDF weighted average embeddings  

# Give a short description on how to run your code
1. Navigate to the code directory
   ```bash
   cd src/Code
2. Install required packages
    ```bash
    pip install torch torchvision torchaudio gensim scikit-learn tqdm jupyter
3. Start the Jupyter notebook
    ```bash
    jupyter notebook term-project.ipynb
4. Execute cells in order
- Data loading & preprocessing
- Vocabulary & embedding setup
- Model training & evaluation
- Result summary and analysis
