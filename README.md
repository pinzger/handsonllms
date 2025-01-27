# My Hands-on LLMs
Python notebooks for the course AI for Software Engineering adopted from the book [Hands-on Large Language Models](https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961). We include example code on:
   * Using an existing tokenizer ("microsoft/Phi-3-mini-4k-instruct"), playing with word2vec embeddings ("glove-wiki-gigaword-50"), training a new word2vec embedding for finding similar songs
   * Using a task-specific BERT model ("cardiffnlp/twitter-roberta-base-sentiment-latest") for classifying movie ratings (without fine-tuning), leveraging the embeddings of SentenceTransformer ("sentence-transformers/all-mpnet-base-v2") to train a classifier for movie ratings
   * Fine-tuning the original BERT model ("bert-base-cased") for classifying movie ratings
   * Continue the pre-training of the original BERT model ("bert-base-cased") using MLM with movie specific data for classifying movie ratings
