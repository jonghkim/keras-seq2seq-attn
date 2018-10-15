# keras-seq2seq-models

*Work-in-Progress*

This is a project to learn different s2s models based on Keras Functional API

## Data
- get the data at: http://www.manythings.org/anki/

## Models
- Vanilla seq2seq model
- Vanilla seq2seq model with attention mechanism
- Pointer network model
- Pointer-Generator model

## Usage
~~~
# For vanilla seq2seq model
python -m bin.seq2seq_model_train
python -m bin.seq2seq_model_test

# For seq2seq with attention mechanism model
python -m bin.seq2seq_attn_model_train
python -m bin.seq2seq_attn_model_test
~~~

### References
- [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215), 2014.
- [Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation](https://arxiv.org/abs/1406.1078), 2014.
- [Get To The Point: Summarization with Pointer-Generator Networks](https://arxiv.org/abs/1704.04368), 2017.