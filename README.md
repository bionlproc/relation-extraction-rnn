# Relation Classification with Bi-LSTM

## Training

```
Usage:
  train.py [options]

Options:
  -h --help                    show this help message and exit
  --word2vec=<file>            word vectors in gensim format
  --dataset=<file>             dataset (see data folder for example)
  --train_ids=<file>           ids of training examples (see data folder for example)
  --dev_ids=<file>             ids of dev exapmles (see data folder for example)
  --test_ids=<file>            ids of test examples (see data folder for example)
  --model=<file>               filename to use to save model
  --num_epochs=<ar>            Max number of epochs [default: 25]
  --mini_batch_size=<ar>       Minibatch size [default: 32]
  --num_classes=<ar>           Total number of classes for training [default: 5]
  --lstm_hidden_state=<ar>     lstm hidden state size [default: 256]
  --random_seed=<ar>           random seed [default: 42]
```

## Acknowledgements

> Ramakanth Kavuluru, Anthony Rios, and Tung Tran. "Extracting Drug-Drug Interactions with Word and Character-Level Recurrent Neural Networks." In Healthcare Informatics (ICHI), 2017 IEEE International Conference on, pp. 5-12. IEEE, 2017.

```
@inproceedings{kavuluru2017extracting,
  title={Extracting Drug-Drug Interactions with Word and Character-Level Recurrent Neural Networks},
  author={Kavuluru, Ramakanth and Rios, Anthony and Tran, Tung},
  booktitle={Healthcare Informatics (ICHI), 2017 IEEE International Conference on},
  pages={5--12},
  year={2017},
  organization={IEEE}
}
```

