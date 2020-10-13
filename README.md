# chatbot_using_reformer

Built a chatbot using reformer model:

Reformer- It helps to get efficient memory and computation for long sequence tasks such as AI storyelling & chatbots.

large datasets such as an entire book are used in these tasks.

Reformer architecture highlights:

1.revnet-reversible layers for saving memory by easy recomputation of activations instead of storing them for n-decoder-layers when doing backpropagation in training..

2.LSH - locally sensitive hashing(LSH) attention reduces the cost of the Dot Product attention for large input sizes.


Dataset used:  MultiWoz dataset

It has more than 10,000 human annotated dialogues and spans multiple domains and topics. Some dialogues include multiple domains and others include single domains.

slots: type of entity discussed

intent/action- action to be taken by bot

Files in this repository :

sample.txt- samples of input and output of chatbot

chatbot+reformer.jpg- reformer model picture
