# Seq2Seq Chatbot

This is a 200 lines implementation of Twitter/Cornell-Movie Chatbot, please read the following references before you read the code:

- [Practical-Seq2Seq](http://suriyadeepan.github.io/2016-12-31-practical-seq2seq/)
- [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
- [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) (optional)

### Prerequisites

- Python 
- [TensorFlow](https://github.com/tensorflow/tensorflow) >= 1.2
- [TensorLayer](https://github.com/zsdonghao/tensorlayer) >= 1.6.3

### Model

<table class="image">
<div align="center">
    <img src="http://suriyadeepan.github.io/img/seq2seq/seq2seq2.png"/>  
    <br>  
    <em align="center"></em>  
</div>
</table>

### Results

<!---#### Twitter-->

```
Query > happy birthday have a nice day
 > thank you so much
 > thank babe
 > thank bro
 > thanks so much
 > thank babe i appreciate it
Query > donald trump won last nights presidential debate according to snap online polls
 > i dont know what the fuck is that
 > i think he was a racist
 > he is not a racist
 > he is a liar
 > trump needs to be president

```

### Chatbot Server
It's a chat loop server to talk with you.

Depend on the output of training result: n.npz

- Run:
  python3 chatbot_svr.py
  
- Entry a chat loop:

```
Query >well 
 > i love you guys
 > i love you guys
 > thank you so much
 > thank you so much for the support
 > i love this show
Query >what is the big news
 > latest in the last time
 > i think its a good idea but its not even close to the end of the season
 > i think the whole same thing is insane
 > latest and the first one
 > the cyber is the best
 ```
<!---
#### Cornell Moive

```

```
-->
