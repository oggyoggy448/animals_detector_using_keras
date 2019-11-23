# Animals detector using keras
## Requirement
1 create a virtual env (optional) using anaconda
2 Install all libraries mentioned in required_libraries file and install their latest version
3 install python 3.7


## dataset
dataset can be downloaded by sending a request to this person using email.
https://app.monstercampaigns.com/c/tortsem7qkvyuxc4cyfi

## Process
### using neural network
1 run train_simple_nn.py file using command prompt with the following command
python train_simple_nn.py -d animals -m output/simple_nn.model -l output/simple_nn_lb.pickle -p output/simple_nn_plot.jpg

2 run predict.py file with following command
python predict.py -d animals -m output/simple_nn.model -l output/simple_nn_lb.pickle -p output/simple_nn_plot.jpg

### using CNN model
1 run train_vgg.py file using command prompt with the following command
python train_vgg.py -d animals -m output/smallvggnet.model -l output/smallvggnet.pickle -p output/smallvggnet.jpg

2 run predict.py file with following command
python predict.py -d animals -m output/smallvggnet.model -l output/smallvggnet.pickle -p output/smallvggnet.jpg
