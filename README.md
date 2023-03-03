# HandsOn
Contains the code for different hands on demontrated.
## SeqToSeq
1. Data will be dowloaded directly using pytorch library "from torchtext.datasets import Multi30k", in the seq2seq.py script
2. Demonstartion can be found in .ipynb file

## Image Captioning
1. Download the dataset used: https://www.kaggle.com/dataset/e1cd22253a9b23b073794872bf565648ddbe4f17e7fa9e74766ad3707141adeb Then set images folder, captions.txt inside a folder Flickr8k.
2. train.py: For training the network
3. model.py: creating the encoderCNN, decoderRNN 
4. get_loader.py: Loading the data, creating vocabulary
5. utils.py: Load model, save model, printing few test cases downloaded online
6. whole demo is given in demo.ipynb

