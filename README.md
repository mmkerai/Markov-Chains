The java class creates a Markov chain frequency table and then uses it to generate sentences.
The quality of the sentence will depend entirely on the input text. The larger and more
grammatically correct the text, the better the generated sentence.

You can use the ngram parameter to determine the length of the word chain. Default is 2.

Usage: 

Markov mc = new Markov(String text); 	// where text is a string full of words separated by spaces.
										// can include sentences and punctuation.

// To generate a sentence:
String sentence = mc.genMarkov(int words); // where words is the number of words to generate

Feedback to admin@thecodecentre.co.uk

