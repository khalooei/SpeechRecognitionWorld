# Keywords

### G2P
Grapheme-to-phoneme (G2P) is a process of converting written words into their corresponding phonetic representation. In speech recognition, G2P models are used to predict the pronunciation of words that are not present in the lexicon or vocabulary.

The process of converting graphemes (letters or groups of letters that represent sound in writing) to phonemes (basic units of sound in spoken language) can be challenging because the same grapheme can represent different sounds depending on the context and language. For example, the letter "a" can represent different sounds in the English words "cat," "father," and "bake."

G2P models typically use machine learning algorithms to learn the mapping between graphemes and phonemes from a large corpus of annotated text data. The most common type of G2P model is the sequence-to-sequence (seq2seq) model, which consists of an encoder network that encodes the input word into a fixed-length representation and a decoder network that generates the output phonemes based on the encoded representation.

Once trained, a G2P model can be used to predict the phonetic transcription of any word, even if it is not present in the training data. This makes G2P models useful for tasks such as converting text to speech, improving speech synthesis, and building speech recognition systems.


### ARPABET
ARPABET (also spelled ARPAbet) is a set of phonetic transcription codes developed by Advanced Research Projects Agency (ARPA) as a part of their Speech Understanding Research project in the 1970s. [ref](https://en.wikipedia.org/wiki/ARPABET)
It represents `phonemes` and `allophones` of General American English with distinct sequences of ASCII characters. 
ARPABET has been used in several speech synthesizers, including Computalker for the S-100 system, SAM for the Commodore 64, SAY for the Amiga, TextAssist for the PC and Speakeasy from Intelligent Artefacts which used the Votrax SC-01 speech synthesiser IC. It is also used in the CMU Pronouncing Dictionary. 
A revised version of ARPABET is used in the [TIMIT](#TIMIT) corpus.


# Datasets
### TIMIT 

TIMIT (TIMIT Acoustic-Phonetic Continuous Speech Corpus) is a corpus of phonemically and lexically transcribed speech of American English speakers of different sexes and dialects. [ref](https://en.wikipedia.org/wiki/TIMIT)
The TIMIT Acoustic-Phonetic Continuous Speech Corpus is a standard dataset used for evaluation of automatic speech recognition systems. 
The TIMIT telephone corpus was an early attempt to create a database with speech samples.
Each transcribed element has been delineated in time. TIMIT was designed to further acoustic-phonetic knowledge and automatic speech recognition systems.
TIMIT was designed to further acoustic-phonetic knowledge and automatic speech recognition systems. It was commissioned by DARPA and corpus design was a joint effort between the Massachusetts Institute of Technology, SRI International, and Texas Instruments (TI).

* 
