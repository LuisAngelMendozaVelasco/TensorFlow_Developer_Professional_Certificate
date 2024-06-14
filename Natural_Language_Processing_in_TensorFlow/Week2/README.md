# Word Embeddings

Last week you saw how to use the Tokenizer to prepare your text to be used by a neural network by converting words into numeric tokens, and sequencing sentences from these tokens. This week you'll learn about Embeddings, where these tokens are mapped as vectors in a high dimension space. With Embeddings and labelled examples, these vectors can then be tuned so that words with similar meaning will have a similar direction in the vector space. This will begin the process of training a neural network to understand sentiment in text -- and you'll begin by looking at movie reviews, training a neural network on texts that are labelled 'positive' or 'negative' and determining which words in a sentence drive those meanings.

## Word Embeddings

- [Video - A conversation with Andrew Ng](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/ONFWD/a-conversation-with-andrew-ng)

- [Video - Introduction](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/1OiEp/introduction)

- [Video - The IMDB dataset](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/PxiP4/the-imdb-dataset)

- [Reading - IMDB reviews dataset](https://www.coursera.org/learn/natural-language-processing-tensorflow/supplement/Z8ypr/imdb-reviews-dataset)

- [Video - Looking into the details](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/0N8WC/looking-into-the-details)

- [Video - How can we use vectors?](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/HKvYY/how-can-we-use-vectors)

- [Video - More into the details](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/U19Cw/more-into-the-details)

- [Lab - Check out the code! (Lab 1)](./Labs/C3_W2_Lab_1_imdb.ipynb)

- [Video - Notebook for lesson 1](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/Q1Ln5/notebook-for-lesson-1)

- [Video - Remember the sarcasm dataset?](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/qXPN7/remember-the-sarcasm-dataset)

- [Video - Building a classifier for the sarcasm dataset](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/WzEOC/building-a-classifier-for-the-sarcasm-dataset)

- [Video - Let’s talk about the loss](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/PmhlZ/lets-talk-about-the-loss)

- [Lab - Check out the code! (Lab 2)](./Labs/C3_W2_Lab_2_sarcasm_classifier.ipynb)

- [Video - Pre-tokenized datasets](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/9IKhR/pre-tokenized-datasets)

- [Reading - TensorFlow datasets](https://www.coursera.org/learn/natural-language-processing-tensorflow/supplement/r1kev/tensorflow-datasets)

- [Video - Diving into the code (part 1)](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/k5GrS/diving-into-the-code-part-1)

- [Reading - Subwords text encoder](https://www.coursera.org/learn/natural-language-processing-tensorflow/supplement/C2ocn/subwords-text-encoder)

- [Video - Diving into the code (part 2)](https://www.coursera.org/learn/natural-language-processing-tensorflow/lecture/RfS7z/diving-into-the-code-part-2)

- [Lab - Check out the code! (Lab 3)](./Labs/C3_W2_Lab_3_imdb_subwords.ipynb)

- [Reading - Week 2 Wrap up](https://www.coursera.org/learn/natural-language-processing-tensorflow/supplement/EO4w5/week-2-wrap-up)

## Lecture Notes (Optional)

- [Reading - Lecture Notes Week 2](./Readings/C3_W2.pdf)

## Weekly Assignment - More on the BBC News Archive

- [Lab - Diving deeper into the BBC News archive](./Labs/C3W2_Assignment.ipynb)