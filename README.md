# ChatBot
Repository contains of python code for building a chatbot using pytorch which can respond to queries in English

### Dataset:
Dataset consists of 10,000 input and target sentences

### Model:

Used Bidirectional Recurrent Neural Network 

<img src="https://github.com/nilakshi104/ChatBot/blob/master/Images/RNN-bidirectional.png" width=500/img>

Model consists of Encoder and Decoder (uses Luong Attention architecture) parts

<img src="https://github.com/nilakshi104/ChatBot/blob/master/Images/seq2seq_ED.png" height=370 width=500/img><img src="https://github.com/nilakshi104/ChatBot/blob/master/Images/global_attn.png" height=350 width=400/img>

### Results:

<img src="https://github.com/nilakshi104/ChatBot/blob/master/Images/Screenshot%20from%202020-09-06%2004-19-24_n.png" width=500/img>

Achieved 32 Bleu Score on above model 

(Compared Human label sentences Vs Chatbot Output sentences to calculate Bleu score so Bleu score obtained is not generalized and is calculated only for a single Human label sentence corresponding to each test sentence)
