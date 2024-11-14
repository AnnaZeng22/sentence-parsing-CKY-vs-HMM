# Introduction
The CKY algorithm is a parsing algorithm that takes a sequence and a context-free grammar in Chomsky Normal Form, and determines whether it can be parsed into a sentence. 

# Files
rules.txt stores a large CFG.

pos files.zip compresses all the files containing part-of-speech tagged sentences from the same corpus derived rules.txt from.

sentences.txt contains sentences to assess two algorithms.


# Approaches 
We construct CKY and HMM algorithms through Python. CKY is a parsing algorithm takes a sequence and a context-free grammar in Chomsky Normal Form, determines whether it can be parsed into a sentence, and goes probabilistic by multiplying probabilities of sentence components. HMM uses the part-ofspeech tagged sentences from a usage-based corpus to estimate its parameters, thus calculating the probabilities
of success in sentence parsing.

# Findings 
 Comparing between algorithms, HMM offers competitive probabilities than CKY. Then we replacethe old probability with the new one estimated by probabilistic rule’s (CFG) parameters. Now, compared within the CKY algorithm, new grammar enhances probabilities compared to the old one.
