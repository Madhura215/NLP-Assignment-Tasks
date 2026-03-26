**Task 1: Conceptual Understanding:**



1.What is the difference between "Love" and "love" in NLP?



* In NLP, these are considered different words due to the case sensitivity.
* "Love" is used at the beginning of the sentence, whereas "love" is used in general sentences.
* In order to prevent duplication, we convert all the text to lowercase.





2.What if we don't remove the stopwords?



* Sentence will look noisy and less meaningful.
* The performance of the model will decrease.
* The important words will have less priority.





3.When removing the stopwords is harmful?

* For Sentiment analysis:

👉 If we have the sentence "I am not happy," and we are removing the word "not," the meaning of the sentence changes.

* For Question Answering:

👉 If we have the sentence "What is your name?" and we are removing the word "what," the sentence is broken.





4. Stemming and Lemmatization

* In Stemming, the words are cut, but the cut words are not necessarily meaningful.

👉 If we have the word "running," we will cut it and make it "run."

* In Lemmatization, the words are Converts to proper root word



