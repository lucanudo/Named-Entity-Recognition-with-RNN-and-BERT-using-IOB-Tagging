# Named-Entity-Recognition-with-RNN-and-BERT-using-IOB-Tagging
The project consists in building two named entity recognition (NER) systems. The systems will make use of the IOB tagging scheme to detect entities of type PER, ORG, LOC and MISC. The tagging scheme thus includes the following tags, assuming one tag per token:

B-PER and I-PER: token corresponds to the start, resp. the inside, of a person's entity
B-LOC and I-LOC: token corresponds to the start, resp. the inside, of a location entity
B-ORG and I-ORG: token corresponds to the start, resp. the inside, of an organization entity
B-MISC and I-MISC: token corresponds to the start, resp. the inside, of any other named entity
O: token corresponds to no entity
Building on the notebooks we've seen during the lectures and on the tips below and in the notebook, you task is to build two tagging models:

a RNN-based model: an embedding layer, a LSTM layer, a feed-forward layer
a fine-tuned BERT tagger: a BERT (pre-trained) layer, a feed-forward layer The final feed-forward layer procudes a probability distribution over the set possible tags for each input token.
Detailed instructions to get started are provided in the notebook. Training, validation and test data are provided in the json.gz dump below.

