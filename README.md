# RNN_search_engine


Stanford CoreNLP server 
pycorenlp
tensorflow

 are needed to run this script

Before runnning main scripts, start CoreNLP server and specify the coreNLP server location

#starting CoreNLP server under CoreNLP home dhirectory
java -mx3g -cp "./*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer [port] [tiemout]
(default port is 9000))

#specifying CoreNLP server location
nlpserver="localhost:9000"

rnn_autoencoder.ipynb
training RNN like autoencoder
term1, term2 -> RNN output -> term1,term2

	
rnn_wordnet.ipynb
training RNN with wordnet definition.
dictionary definition -> word

