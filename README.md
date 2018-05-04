# Star Wars Text Generator

In this Jupyter Notebook we try to generate text based on the dialogues from the Star Wars scripts (episodes IV,V, and VI), based on the usage of N-grams.

All the information for this exercise has been retrieved from the [Visualizing Star Wars Movie Scripts](https://github.com/gastonstat/StarWars) project.

We start by reading all the dialogue lines from the scripts, which are labeled with the character speaking. We are only considering Luke, Leia, and Han Solo. We left Chewbacca out of the example for obvious reasons... We read all the lines of each character and combine them in one single string. We tokenize this string using the WordPunctTokenizer and use these tokens to create an NLTK Text object.

This is by far not the best way of implementing the text generation method, but rather a verbose way intended to exemplify the usage of N-grams.
