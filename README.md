# CS496-DL-for-Proctitioner
This is course project for CS496
The link to the paper of my interest:
https://arxiv.org/pdf/1706.03762.pdf

The website that I think is helpful to understand Transformer:
https://medium.com/inside-machine-learning/what-is-a-transformer-d07dd1fbec04

Codebase that I prepare to base on to develop my project:
https://github.com/SamLynnEvans/Transformer

Review of the paper:

Introduction: 
Transformer is a state-of-art archetitecture to take care of semantic analyis via parallel computing computations. Compared with trandition RNN structure, the muti-head attention mechanism can process the whole paragraph
or multiple sentences in total to obtain their interrelationship.

Procudures and Features: 
In Transformer, encoder positioner, multi-head attention mechanism and feedforward comprise a 
complete unit. The encoder position is for marking the word position in each sentence, which can effectively ensure the 
position of each word can be fully considered in sentence analysis. When it comes to the multi-head attention mechanism,
there are three trainable matrices: k,q,v for dividing samples into mutiple head and analyze their attention relationship
saparately under parallel computing. In the meanwhile, the word dependence will be preserved due to former postional encoding. 
Finally, the processed samples pass the feed-forward, which is composed of mutiple receptrons to serve as gradient descent during the back-propagation.

Timeline of my reproduction:

week 2-week 3: 
Try to run the Transformer smoothly and fully understand the codebase.

week 4-week 6: 
Try to firstly use encoder and connect it with a classfier to do text classification.

week 7-week 8: 
Try to train the model regarding the classification issue and explore machine translation pathway.

week 9-final: 
Try to achieve machine translation with both encoder and decoder.




