# TF-IDF_of_text_file_using_NLTK
### summarize automatically the given text using TF-IDF algorithms.

## Task Competed:

* Convert the input text to a list of sentences. Then, compute the number of sentences in the given Text.
* Calculate the frequency of words in each sentence: the output should be a dictionary where each key is a sentence and the value is also a dictionary of word frequency.
* Calculate Term frequency for each word in a sentence: TF(word)=(Number of times term \word" appears in a sentence) / (Total number of terms in the sentence)
* Create a matrix termFrequency: The termFrequency matrix should be a dictionary where each key is a sentence and the value is also a dictionary of word frequency.
* For each word compute how many sentences contain that word.
* Calculate IDF for each word in a sentence. IDF(word) = log e(Total number of sentences/ number of sentences with term word in it)
* Compute the TF-IDF for each word in each sentence.
* Use the TF-IDF computed in (7) and give a weight for each sentence.
* Threshold: compute the average sentence weight
