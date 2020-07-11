# NMT
神经机器翻译相关代码

文件LSTM_Attention_Seq2Seq 中是用LSTM实现的Seq2Seq模型。编码器为biLSTM，解码器为俩层LSTM。

训练语料为2000条中-英平行句对，在验证集上的BLEU=14.08， 在测试集上的BLEU=13.80
