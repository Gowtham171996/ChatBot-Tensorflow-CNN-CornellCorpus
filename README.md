# Seq2Seq Chatbot

This is a 200 lines implementation of Twitter/Cornell-Movie Chatbot, please read the following references before you read the code:

- [Practical-Seq2Seq](http://suriyadeepan.github.io/2016-12-31-practical-seq2seq/)
- [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
- [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) (optional)

### Prerequisites

- Python 3.6
- [TensorFlow](https://github.com/tensorflow/tensorflow) >= 2.0
- [TensorLayer](https://github.com/zsdonghao/tensorlayer) >= 2.0

### Model

<table class="image">
<div align="center">
    <img src="http://suriyadeepan.github.io/img/seq2seq/seq2seq2.png"/>  
    <br>  
    <em align="center"></em>  
</div>
</table>

### Training

```
python3 main.py
```
<table class="image">
<div align="center">
    <img src="https://github.com/Gowtham171996/ChatBot-Tensorflow-CNN-CornellCorpus/blob/master/images/Train.PNG"/>  
    <br>  
    <em align="center"></em>  
</div>
</table>

### Testing

```
python3 Chatwithbot.py
```
<table class="image">
<div align="center">
    <img src="https://github.com/Gowtham171996/ChatBot-Tensorflow-CNN-CornellCorpus/blob/master/images/Chat.PNG"/>  
    <br>  
    <em align="center"></em>  
</div>
</table>

### Results

```
Welcome to Chatbot
Hi, I am Chatbot.
do you listen to this crap?
 > what about your people
no they wont listen
 > i dont think so
really they wont listen
 > why dont you ask them
ok i will ask them then
 > so what makes you think i think its a true idea
well i believe in you
 > i suppose i did
