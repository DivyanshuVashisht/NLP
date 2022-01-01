# Question/Answer System

### Pre-Trained Transfer Model - ALBERT
It is said that ALBERT(A Lite BERT) has shorter training and inference times than BERT(Bidirectional Encoder Representations from Transformers). 
We would be fine tuning ALBERT FOR our Q&A task.

Note: This notebook performs computationally expensive tasks. Make sure you use a GPU/TPU while training the Model. Using Google Colab Pro version over the free one is HIGHLY recommended.

We have also used the [Hugging Face Library](https://github.com/huggingface/transformers/)

The training data is obtained from the [SQuAD2.0 dataset](https://rajpurkar.github.io/SQuAD-explorer/), The Stanford Question Answering Dataset.

Finally at the end the model is tested against arbitray contextual passages. You are free to add you own Passages to test this amazing project out.
