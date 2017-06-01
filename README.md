# tf-stanford-tutorials Chatbot
This repository contains the code example for a Chatbot from the course CS 20SI: TensorFlow for Deep Learning Research at Stanford University<br>

It is a complete but primitive neural chatbot using sequence to sequence model with attentional decoder in TensorFlow. Originally it was created by Chip Huyen as the starter code for an assignment «TensorFlow for Deep Learning Research» cs20si.stanford.edu﻿

Original Github code repo:
https://goo.gl/QH6M6E

A companion assignment instructions sheet:  web.stanford.edu - 
https://goo.gl/vfGQI4

Claude Coulombe updated the code in order to be compatible wit h Python 3 and TensorFlow 1.1. On May 31 2017, it seems to work correctly but have not the computing ressources to train it for a long period of time.<br>

Detailed syllabus and lecture notes can be found at http://cs20si.stanford.edu
<br>

Using the Chatbot<br>
-----------------<br>

1) Check out this repository. <br>
git clone https://github.com/ClaudeCoulombe/tf-stanford-tutorials.git<br>

2) Download and unzip the dataset and put it in the data sub-folder<br>
https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html<br>

3) Change the DATA_PATH in the config.py, line 20<br>

4) Then run the data.py file<br>
python data.py<br>
It should create the folder 'processed', and then put a bunch of data files into it.<br>

5) Train the model<br>
python chatbot.py --mode train<br>
You could interrupt it after a long time or when the loss is low enough<br>
since the TensorFlow model is saved in the checkpoints folder you can recover the models<br>

6) Interact / play with the Chatbot<br>
python chatbot.py --mode chat<br>







