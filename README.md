# My Hands-on LLMs
Python notebooks for the course AI for Software Engineering adopted from the book [Hands-on Large Language Models](https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961). We include example code on:
   * Using an existing tokenizer ("microsoft/Phi-3-mini-4k-instruct"), playing with word2vec embeddings ("glove-wiki-gigaword-50"), training a new word2vec embedding for finding similar songs
   * Using a task-specific BERT model ("cardiffnlp/twitter-roberta-base-sentiment-latest") for classifying movie ratings (without fine-tuning), leveraging the embeddings of SentenceTransformer ("sentence-transformers/all-mpnet-base-v2") to train a classifier for movie ratings
   * Using a pre-trained T5 model ("google/flan-t5-small"") for classifying movie ratings (without fine-tuning)
   * Fine-tuning the original BERT model ("bert-base-cased") for classifying movie ratings, fine-tuning only the classification head and show the difference in performance
   * Continue the pre-training of the original BERT model ("bert-base-cased") using MLM with movie specific data and fine-tune the model for classifying movie ratings
   * Show various prompting strategies (zero-shot, one-shot, chain-of-thought, ...) with the "microsoft/Phi-3-mini-4k-instruct" model
   * Fine-tuning "TinyLlama/TinyLlama-1.1B-Chat" using quantization and LoRA (QLoRA) to generate "better" answers for questions, including merging, saving, loading, and evaluating such a model 
   * Another example fine-tuning a quantized "TheBloke/CodeLlama-7B-Instruct-GPTQ" model with LoRA taken from the AIware Leadership Bootcamp 2024
