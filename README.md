## Neural Machine Translation (NMT) for Spanish to English

Encoder-Decoders have been used in many applications to change the form of data. In terms of languages, it could be used to translate among different languages. In the above project an Encoder-Decoder structure has been used to translate from Spanish to English. There may be two main approaches for this mechanism

1. Char based translation
2. Word based translation

Each of these methods have their own benefits and drawbacks, Word based networks tend to learn the distribution of the dataset faster, since char based networks not only have to learn the features of translation, but also they should learn the language model. A char based network may generate meaningless words in case where the network has not been trained well.

The implemented project is based on characters, It is a Encoder-Decoder structure based on LSTM networks, where each sentence in the input is converted to a latent vector, afterwards fed to a LSTM network to generate the translated sentence in destination language.
