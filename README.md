# NN_Boltzmann
## 概要
[ボルツマンマシン](https://ja.wikipedia.org/wiki/%E3%83%9C%E3%83%AB%E3%83%84%E3%83%9E%E3%83%B3%E3%83%9E%E3%82%B7%E3%83%B3)に基づいた[N-Queen](https://ja.wikipedia.org/wiki/%E3%82%A8%E3%82%A4%E3%83%88%E3%83%BB%E3%82%AF%E3%82%A4%E3%83%BC%E3%83%B3#n-%E3%82%AF%E3%82%A4%E3%83%BC%E3%83%B3)の解法のPython実装  

主眼は、N-Queenの解を求めることではなく、相互結合型ニューラルネットワークを使うことにある。  
したがって、N-Queenの解を求めるだけであれば、様々な工夫ができるが、それはあえて行わず、エネルギーの減衰を素直に実装した。

