# NLP Webinar

This is the repository of all the source code that we have used in the project walkthroughts. 
1. GOT Walkthrough - This is the project where we learn about NLP using the dataset of character dialogues from Game of Thrones. Topic Modelling, Sentiment Analysis and Text Generation are covered here.
2. Chatbot - This is an attempt at building a ChatBot using Seq2Seq model. This model is based on 2 [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory) Layers. Seq2Seq mainly consists of 2 components i.e Encoder and Decoder, hence sometimes it is also called Encoder-Decoder network.
3. Word Embeddings - In this project, we covered exercises on 5 word embeddings: CountVectorizer, TFIDF, Word2Vec, Glove and FastText.
4. Sarcasm Detection - In this project, we use FastText word embeddings to detect if a comment is sarcastic or not.

| Project Walkthrough  | Slides Link | Recording Link |
| -------------------- | ------------| ---------------|
| Game of Thrones | [Link](https://drive.google.com/open?id=1k_pNYWRD2u9-y-JmP_Q887Kh4hJ07dv8) | [Link](https://bit.ly/DLQRec3) |
| Chatbot | [Link](https://drive.google.com/open?id=1k_pNYWRD2u9-y-JmP_Q887Kh4hJ07dv8) | [Link](https://bit.ly/DLQRec3) |
| Word Embeddings | [Link](https://drive.google.com/open?id=1IR8BkIgIkatbUWE5k8pWLyYN1zdO6HjA) | [Link](https://bit.ly/DLQRecNLP2) |
| Sarcasm Detection    | [Link](https://drive.google.com/open?id=1IR8BkIgIkatbUWE5k8pWLyYN1zdO6HjA) | [Link](https://bit.ly/DLQRecNLP2) |



#### For chatbot, download dataset - Cornell Movie-Dialogs Corpus
```http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html```

### Run the notebooks using Google Colab
#### Why use google colab?
1. It allows you to execute a runtime instance using google's GPU (which is a powerful Nvidia Tesla K80) coupled with 12GB Ram
2. It is free of cost
3. Only downside is that it allots you a time period of 12 hours maximum after which the runtime terminates without any warnings and any files in that runtime are deleted as well
