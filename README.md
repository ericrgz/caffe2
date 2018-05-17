#CAFFE2

## Instruction for test  
sudo docker run -it --runtime=nvidia --rm caffe2ai/caffe2 bash
cd /caffe2/caffe2/python/examples
wget https://caffe2.ai/static/datasets/shakespeare.txt
wget https://raw.githubusercontent.com/pytorch/pytorch/master/caffe2/python/examples/char_rnn.py
python char_rnn.py --train_data shakespeare.txt


#Todo
Create the dapp 